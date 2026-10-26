# RigWorks Studio on Linux

RigWorks Studio is a Windows app. On Linux it runs through **Wine**, set up by an install script that downloads the latest release, checks it, and adds a desktop shortcut. From version 0.2.3 the app finds your game and profiles by itself and updates itself, just like on Windows.

> Linux support is community supported. The install script is made by Pootis.

## What you need

- **Euro Truck Simulator 2**: the native Linux version, or the Windows version through Steam Play (Proton). Both work.
- **A desktop Linux distro** that uses `apt`, `dnf`, `pacman` or `zypper` (Ubuntu, Debian, Mint, Fedora, Arch, openSUSE and others).
- **About 1 GB of free space.**

You don't need Wine installed beforehand. The script installs what's missing (`curl`, `7-Zip` and `Wine`) after asking you, and you may need to enter your password.

RigWorks Studio needs **Wine 9 or newer**. Some distros ship older versions; the script warns you if yours is too old and points you to [WineHQ's packages](https://gitlab.winehq.org/wine/wine/-/wikis/Download).

## Install

1. **Download the install script.** Open a terminal and run:

   ```bash
   cd ~
   curl -fLO https://github.com/M1sterchamp/RigWorks-Studio/releases/latest/download/install-rigworks.sh
   ```

   You can also download `install-rigworks.sh` from the newest release on the [Releases page](https://github.com/M1sterchamp/RigWorks-Studio/releases) and save it in your home folder. You don't need the `.exe`; the script downloads it for you.

2. **Allow it to run:**

   ```bash
   chmod +x install-rigworks.sh
   ```

3. **Run it:**

   ```bash
   ./install-rigworks.sh
   ```

   It checks your tools, offers to install any that are missing, finds the newest release, and asks where to install. Press Enter for the default folder, `~/rigworks-app`.

   > **Debian or Ubuntu and Wine won't install?** Wine needs 32-bit support first. Run `sudo dpkg --add-architecture i386`, then run the script again.

4. **Open RigWorks Studio** from the shortcut on your desktop or in your application menu.

The app finds your game and profiles by itself: native ETS2, the Windows version through Proton, Flatpak Steam, and Steam Cloud profiles.

## If it can't find your game or profiles

This is only needed for unusual setups. Point RigWorks Studio at the folders once and it remembers them.

Wine shows your Linux files as drive `Z:`. In the app's folder picker you can paste a path straight into the folder box, which is easier than clicking because folders starting with a dot are often hidden. Replace `yourname` with your Linux username (run `whoami` if you're not sure).

**The game:** in Render Mode, click **Game…** and pick the folder that contains `base.scs`. For a normal Steam install:

```
Z:\home\yourname\.local\share\Steam\steamapps\common\Euro Truck Simulator 2
```

If your Steam library is on another drive, use that library's `steamapps\common\Euro Truck Simulator 2` folder instead.

**Your profiles:** open **Settings**, find the Euro Truck Simulator 2 folder and click **Change folder…**. Pick the one for your setup:

| Your setup | Profiles folder |
|---|---|
| Native Linux ETS2 | `Z:\home\yourname\.local\share\Euro Truck Simulator 2` |
| Windows ETS2 through Proton | `Z:\home\yourname\.local\share\Steam\steamapps\compatdata\227300\pfx\drive_c\users\steamuser\Documents\Euro Truck Simulator 2` |
| Flatpak Steam, native ETS2 | `Z:\home\yourname\.var\app\com.valvesoftware.Steam\.local\share\Euro Truck Simulator 2` |
| Steam Cloud profiles | `Z:\home\yourname\.local\share\Steam\userdata\NUMBER\227300\remote` (`NUMBER` is your Steam account's folder) |

The right folder has a `profiles` or `steam_profiles` folder inside it. Once you choose a folder, the app only lists profiles from it; click **Find automatically** in Settings to go back.

## Using your mods in the game

Paint job mods are saved straight into the game's `mod` folder by default. Other save dialogs can open in Wine's own folders, so move to your profiles folder (from the table above) before saving.

| You exported | Where it goes |
|---|---|
| A paint job mod (`.scs`) | The `mod` folder inside your profiles folder. Then tick it in the game's Mod Manager. |
| A local mod skin (`.zip`) | Extract it straight into your profiles folder, so its `codes.txt` ends up inside it. |
| A truck sent to your save | RigWorks writes it into the save for you. Close the game first; RigWorks warns you if it's still open. |

## Things that work differently on Linux

- **Updates install through the Linux script.** When a new version is out, the app offers it as on Windows. Click **Update**, wait while it downloads and installs, then click **Restart**. If an update fails, your current version stays as it was, and running the script again in a terminal finishes the job.
- **The 3D view may be slower than on Windows**, because the graphics go through Wine. Lowering the screenshot size or turning off rain helps on weaker graphics cards.
- **Steam Deck isn't covered.** SteamOS doesn't let the script install Wine and 7-Zip.

## Update, reinstall or remove

**Update by hand:** the app offers updates itself, but you can also run the script again. It updates your install, or tells you you're already up to date.

```bash
~/install-rigworks.sh
```

**Install without questions, or to another drive:** `-y` answers yes to everything except deleting files; `-d` picks the install folder.

```bash
~/install-rigworks.sh -y
~/install-rigworks.sh -d /mnt/data
```

**Shortcut missing or broken:** recreate the shortcuts without downloading anything.

```bash
~/install-rigworks.sh --shortcuts
```

**Remove RigWorks Studio:** removes the app and its shortcuts, then asks separately whether to delete your RigWorks settings, fonts and save backups. Your game, saves and exported mods aren't touched.

```bash
~/install-rigworks.sh --uninstall
```

All options: `~/install-rigworks.sh --help`.

## If something goes wrong

**The app doesn't open.** Its output is saved to a log file. Look at the end of it, or send it when asking for help:

```bash
tail -n 50 ~/.cache/rigworks-studio.log
```

The previous run's log is `~/.cache/rigworks-studio.log.1`.

**The app installs but doesn't start.** The most common cause is an old Wine. Check with `wine --version`; you need Wine 9 or newer.

**An update failed.** Your current version is left as it was. The update's log is here:

```bash
tail -n 30 ~/.cache/rigworks-update/update.log
```

Running the script again in a terminal usually sorts it and shows any problem on screen.

**"Couldn't reach GitHub" or "doesn't match the release's checksum".** The first means the script couldn't download the release details: check your internet connection and try again. The second means the download was damaged on the way, so the script refused to install it. Run the script again.

**The app can't find the game or my profiles.** Set the folders by hand as described in [If it can't find your game or profiles](#if-it-cant-find-your-game-or-profiles). The game folder must contain `base.scs`, and the profiles folder must contain `profiles` or `steam_profiles`. Paths are case-sensitive on Linux, so copy them exactly.

For anything else, ask in the [RigWorks Studio Discord](https://discord.gg/FmYvK2Uxwt) and include your distro, your ETS2 setup (native or Proton), and the end of the log file.

---

RigWorks Studio is made by M1sterchamp. The Linux install script is made by Pootis. RigWorks Studio is a fan-made tool and isn't affiliated with or endorsed by SCS Software.
