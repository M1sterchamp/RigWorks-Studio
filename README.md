<div align="center">

<img src="https://i.postimg.cc/KYFXw84N/taskbar.png" width="120" />

# RigWorks Studio

**See your Euro Truck Simulator 2 trucks in 3D, customise them outside the game, and export them.**

[![Latest release](https://img.shields.io/github/v/release/M1sterchamp/RigWorks-Studio?include_prereleases&label=version&color=4f7cff&style=for-the-badge)](https://github.com/M1sterchamp/RigWorks-Studio/releases/latest)
[![Downloads](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fsupervisions.elitecc.uk%2Frigworks%2Fdownloads&query=%24.download_count&label=DOWNLOADS&suffix=%20Latest%20Version&color=2ea44f&style=for-the-badge)](https://github.com/M1sterchamp/RigWorks-Studio/releases/latest)
[![Overall Downloads](https://img.shields.io/github/downloads/M1sterchamp/RigWorks-Studio/total?label=OVERALL%20DOWNLOADS&color=5266ff&style=for-the-badge)](https://github.com/M1sterchamp/RigWorks-Studio/releases)
![Status: beta](https://img.shields.io/badge/status-beta-f0883e?style=for-the-badge)
[![Discord](https://img.shields.io/discord/1554485297226715236?label=Discord&logo=discord&logoColor=white&color=5865F2&style=for-the-badge)](https://discord.gg/FmYvK2Uxwt)

![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white)
![Euro Truck Simulator 2](https://img.shields.io/badge/Euro%20Truck%20Simulator%202-supported-e8a33d)
![Electron](https://img.shields.io/badge/Electron-44-47848F?logo=electron&logoColor=white)
![three.js](https://img.shields.io/badge/three.js-r186-222222?logo=threedotjs&logoColor=white)
![Blender export](https://img.shields.io/badge/Blender-export-E87D0D?logo=blender&logoColor=white)
![Discord Rich Presence](https://img.shields.io/badge/Discord-Rich%20Presence-5865F2?logo=discord&logoColor=white)

[![Issues](https://img.shields.io/github/issues/M1sterchamp/RigWorks-Studio?label=OPEN%20ISSUES&color=e67e22&style=for-the-badge)](https://github.com/M1sterchamp/RigWorks-Studio/issues)
[![Stars](https://img.shields.io/github/stars/M1sterchamp/RigWorks-Studio?label=STARS&color=f1c40f&style=for-the-badge)](https://github.com/M1sterchamp/RigWorks-Studio/stargazers)
![Latest Release](https://img.shields.io/github/release-date/M1sterchamp/RigWorks-Studio?label=LATEST%20RELEASE&color=5266ff&style=for-the-badge)

[**⬇️ Download**](https://github.com/M1sterchamp/RigWorks-Studio/releases/latest) · [**✨ Features**](#-render-mode) · [**📸 Screenshots**](#-screenshots) 

<br />

<img src="https://i.postimg.cc/rs5CBMDF/render-day.jpg" width="100%" />

</div>

RigWorks Studio is a Windows desktop app that reads ETS2's own game files and rebuilds trucks and trailers exactly as the game defines them: every cab, chassis, accessory, paint job, light and interior.

- 🚚 **Look at your truck from your save** in 3D, day or night, with working lights.
- 🛠️ **Plan a build in the Save Edit Builder** and get a save-edit code for Project-ALM and other save tools.
- 🎮 **Send it straight to the game**: export a truck or trailer into one of your saves in two clicks, or import the one you're driving.
- 🚚 **Build trailers too**: doubles, B-doubles and custom sets, loaded with any cargo the game has, lashed down and plated.
- 📦 **Export it as a 3D model** for Blender, game engines and other 3D software.

> [!NOTE]
> RigWorks Studio is a fan-made tool. It is not affiliated with or endorsed by SCS Software. You need your own copy of Euro Truck Simulator 2.

---

## 🚀 Getting started

**You need:** Windows 10 or 11 (64-bit) and Euro Truck Simulator 2 (Steam or other installs; DLCs you own are picked up automatically). **Blender** is optional, and only needed for `.blend` and OBJ exports.

1. **Download** the latest installer from the [Releases](https://github.com/M1sterchamp/RigWorks-Studio/releases/latest) page and run it.
2. **Open RigWorks Studio.** It finds your ETS2 install through Steam and reads the game's archives directly, so there's nothing to unpack. If it can't find the game, use **Game…** to choose the folder containing `base.scs` and `def.scs`.
3. **Choose a mode** on the start page:
   - 🎬 **Render Mode**: build a truck from your save, look around it, screenshot it or export it.
   - 🛠️ **Save Edit Builder**: start from a dealer truck (or import your own), change its paint and parts, then export it straight to your save or get a save-edit code.
   - 🚚 **Trailer Save-Edit Builder**: the same for owned trailers, with combinations, cargo and licence plates.

<p align="center">
  <img src="https://i.postimg.cc/xdTvyYH9/home.png" width="85%" />
</p>

---

## 🎬 Render Mode

Rebuild a truck from your save and look at it in 3D, by day or night, with working lights, in a photo studio if you like.

- 🧾 **Build your truck from your save**: paste its `vehicle_*_accessory` units or import a `.txt` file (drag and drop works too).
- 🚛 **Add an owned trailer** and it is hitched up, with its cargo, lashing and licence plate.
- 🔍 **Browse every truck and trailer model** in the game and your DLCs, and click any part for its details.
- 📸 **Photo studio**, night, rain and game-style reflections.
- 💡 **Working lights**, beacons, strobes, indicators, wipers and turning wheels.

<details>
<summary><b>More about Render Mode</b></summary>

### 🧾 Building from your save
- 🔖 **Licence plates** show your plate text, typed in or read from the save's `license_plate` line.
- A **build report** lists any part that couldn't be shown, such as parts from mods or DLCs you don't have.
- Clicking a part shows its name, category, price, icon and the game files it comes from.

### 🌗 Scene options
| Option | What it does |
|---|---|
| 🪞 **Reflections** | A neutral studio setup, or game-style reflections |
| 🌙 **Night** | Dark scene with working headlight beams lighting up the ground |
| 🌧️ **Rain** | Wet weather *(heavy on the graphics card)* |
| 📐 **Grid** | A floor grid under the truck |
| 📍 **Attachment points** | The game's mount locators |
| 🚛 **Trailer** | Show or hide the hitched trailer |
| 📸 **Studio** | Puts the vehicle in a photo studio |

### 📸 Photo studio
Turn on **Studio** in the **Scene** menu and the vehicle stands in a car photo studio: a seamless curved backdrop, softboxes on stands, and reflections of the studio in the paint and chrome. It works in every mode, and your settings are remembered between sessions.

| Option | Choices |
|---|---|
| 💡 **Lights** | **Soft** (even, all-round), **Dramatic** (strong key and rim light, deep shadows) or **High key** (bright and flat) |
| 🎨 **Backdrop** | **White**, **Grey** or **Black** |
| 🪞 **Glossy floor** | A polished floor that mirrors the vehicle *(heavier on the graphics card)* |
| 🔄 **Turntable spin** | Slowly turns the vehicle on the studio's turntable |

### 💡 Working lights and animation
| Toggle | What lights up or moves |
|---|---|
| **Lights** | Headlights, high beams, red tail lights, roof and aux lights, marker lights and decorative lights |
| **Beacons** | Rotating beacons pulse, and LED strobes flash in a real double-flash pattern, small but bright enough to light what's around them |
| **Brake lights** | The brake lamps, lit across the whole lamp as in game |
| **Indicators** | Left, right or hazards in amber, in the right part of each head and tail lamp, with running indicators where the truck has them |
| **Wipers** | The game's own animations, including the mirrored UK-cab versions |
| **Wheels turning** | The wheels spin as if the truck is driving |

</details>

---

## 🛠️ Save Edit Builder

Design a truck from any dealer configuration in the game, then send it to your save or take it as a save-edit code.

- 🏪 **Pick a base truck** from every dealer truck in the game, or import your own from a code or [straight from your save](#-export-to-game-and-import-from-game).
- 🎨 **Paint** it with any paint job that fits the cab, and change its colours with a live preview.
- 🔧 **Change parts** by clicking pins on the truck, inside the cab as well as outside.
- 📋 **Take it to the game** with **Export to game…**, or with **Save-edit code…** for **Project-ALM** and other save editors.

<p align="center">
  <img src="https://i.postimg.cc/x8LywnXf/parts.jpg" width="85%" />
</p>

<details>
<summary><b>More about the Save Edit Builder</b></summary>

### 🏪 Picking a base truck
- Browse dealer trucks by brand, or search (e.g. `FH6 globetrotter 6x2`).
- Pick a different **chassis** before you start. Parts that don't suit it are swapped for ones that do.
- 📥 **Import your own truck**: paste its units from Project-ALM or another save tool, open a `.txt` file, or use **Import from game…**.

### 🎨 Paint
- Paint jobs are sorted into **Colours**, **Metallic** and **Designs**, with search.
- Paint jobs that allow it let you change the base colour and colours 1–3.

### 🔧 Parts
- 📍 **Click-to-edit pins** show every place a part can go. Click one to swap the part, fit a new one, or remove it.
  - Pins sit on the actual part, and paired parts (mirrors, sideskirts, fenders, steps, lights) get one on each side.
  - Empty slots show where a part *would* go. Every axle has wheel pins, and parts like light bars and bull bars have a small pin for each **light slot**.
  - 👁️ Hide or show the pins with the button in the view or the <kbd>P</kbd> key.
- 🪑 **Inside the cab**: the interior view puts the camera at the driver's head, to add or change dashboard sets, bed and seat items, hanging toys, curtains, windshield sets, steering wheels and more.
- 🗂️ **Part picker**: parts made for your truck come first, with price and icon.
  - **Show all** lists parts that may not fit, marked ⚠️ with the reason (for example, "made for the high sleeper cab").
  - **Other truck brands** borrows the same kind of part from another truck.
  - ➕ **Add as an extra part** stacks a second part on the same pin, a common save-editing trick. Each copy gets its own pin.
- 💡 **Lights on accessories**: fit any light in the game to a light slot. Lights made for that spot are listed first.
- ⚙️ **Core parts**: change the **chassis, cab, engine, transmission, headlights and interior**, including options from other trucks.
- 🤝 What the game does automatically is done for you. Fitting digital camera mirrors, for example, also adds their screens inside the cab.
- 🖌️ **Paint individual parts** with a colour picker, a reset to the part's own colour, and ⭐ **favourite colours** you can save and reuse.
- ⚠️ Warnings when a part may not work in game, and a **⚠ Remove** button for parts the truck needs.
- ↩️ **Undo** (<kbd>Ctrl</kbd> + <kbd>Z</kbd>) for every change, and a searchable list of every part on the truck.

### 📋 The save-edit code
**Save-edit code…** gives you the whole truck as save units. 📋 Copy it to the clipboard or 💾 save it as a `.txt` file.

</details>

---

## 🎮 Export to game and import from game

Skip the copying and pasting: RigWorks Studio reads and writes your Euro Truck Simulator 2 saves itself, for trucks and for trailers, including doubles and custom sets.

1. Build your truck or trailer, then click **Export to game…** at the bottom of the editor.
2. Pick the **profile** and the **save**. Both are listed by the names you see in game.
3. Click **Export to game**, then load that save in ETS2.

> [!WARNING]
> Exporting **overrides your currently active vehicle** in the save you pick. A truck replaces the truck you're driving. A trailer replaces the trailer hooked up to it (and any trailers behind it), keeping its place in your garage.

<p align="center">
  <img src="https://i.postimg.cc/7LY3MD7x/export-to-game.png" width="85%" />
</p>

<details>
<summary><b>More about exporting and importing</b></summary>

- 💾 **A backup is made first.** The save is copied before anything is written, and **Show backup** opens the copy so you can put it back. The last 10 backups of each save are kept.
- 🎮 **If the game is open**, load the save from the game's menu after exporting, and don't save over it from the game you already have open.
- 📥 **Import from game…** in the truck or trailer dealer loads the truck you're driving, or the trailer hooked up to it, from the save you pick. It opens in the editor with its paint, parts and licence plate, ready to change and export back. Importing only reads the save.
- 📁 **Finding your saves**: profiles are found automatically in `Documents\Euro Truck Simulator 2`, both local and Steam Cloud. If yours live somewhere else, set the folder in **Settings → ETS2 profiles folder**.

</details>

---

## 🚚 Trailers and cargo

The **Trailer Save-Edit Builder** does for owned trailers what the Save Edit Builder does for trucks: pick one at the trailer dealers (or import yours, from a code or [straight from your save](#-export-to-game-and-import-from-game)), change its paint and parts with the same pins, load it, and export it to the game or take the save-edit code.

- 🔗 **Doubles, B-doubles and HCT**, plus custom sets of any make, up to B-triples and drawbar triples.
- 📦 **Any cargo the game can show**, with your choice of how many and whether it carries real weight.
- ⛓️ **Lashing** with the game's own straps, chains, ratchets and hooks.
- 🔖 **Licence plates** on every trailer, and **ADR plates** on dangerous goods.

<p align="center">
  <img src="https://i.postimg.cc/tR33LWq6/cargo-combination.png" width="85%" />
</p>

<details>
<summary><b>More about trailers and cargo</b></summary>

### 🔗 Doubles, B-doubles and HCT
- **Combination** (in the dealer, and at the top of the editor) turns a trailer into any set-up the game's trailer shop offers for it: single with any axle count, **double**, **B-double** or **HCT** (trailer + dolly + trailer). Pick the **bodies** for the whole set, and every trailer and dolly gets the chassis, parts and wheels it needs.
- Switch between **Trailer 1 · Dolly · Trailer 2** (or click one in the view) to edit its parts. The paint job is shared across the combination.
- 🧩 **Build custom set…** hitches trailers and dollies of **any make** together: B-doubles, **B-triples**, HCTs and **drawbar triples**.
  - The game's limit is 3 units. Dollies count, so a triple has no dolly.
  - Start from a preset, then pick each unit's trailer, chassis and body.
  - Each unit is checked against the coupling in front: a semi-trailer goes on a fifth wheel (B-double lead or dolly), a dolly or drawbar trailer on a hook.
  - The game's shop doesn't sell most of these, so they're at your own risk.

### 📦 Cargo
- 🟢 **The green pin** on a trailer opens its cargo: every load the game can show, each with a **picture drawn from its model**. Loads the body is made to carry come first; **Show all** lists the rest, marked ⚠️ with the reason they may not work in game.
- **Loose loads and containers** fill the loading area, and you choose **how many**. Machines and other fixed loads sit where the game puts them on that body.
- **Each trailer of a combination has its own cargo.** **Copy to all** loads every other trailer with the same one, as much as each holds.
- ⚖️ **Real weight**: tick it to give the trailer the cargo's weight in game. Unticked, the load is only for show and the trailer drives as if empty.
- ℹ️ **Cargo details**: select a cargo (or point at one in the list) for its category, size, mass, volume, pay rate, fragility, ADR class, and which trailers haul it.

### ⛓️ Lashing
- Loads that are tied down are shown tied down, with the game's own gear: **straps with ratchets**, **chains with binders**, and the **hooks** on each end.
- Straps and chains run from the trailer's lashing rail, over the load, to the rail on the other side. Machines are chained from their own lashing points straight to the trailer.
- Trailers with **tie-down rings** (lowbeds and low loaders) show them along the deck, raised where something is hooked on.

### 🔖 Licence plates and hazard plates
- Type a **licence plate** for each trailer (`AB12 CDE|uk`: the text, then the country). It's shown on the trailer as you type and written to the save.
- **Dangerous goods** come with their **ADR plates and diamonds**, on the trailer's own mounting points.

### 📋 The trailer's save-edit code
- A **combination's** code has one `trailer` unit per trailer or dolly, linked in order, each with its own parts, cargo, cargo weight and licence plate. Type your trailer's ID and its `trailer_definition` from the save and the first unit takes them, so you can swap it straight into `game.sii`. Sets imported from your save keep both automatically.
- A **single trailer's** code is its parts and its cargo. The code window tells you what else to set on your trailer's own unit: listing the cargo among its accessories, its weight and its licence plate.

</details>

---

## 📦 Exporting 3D models and pictures

Save what's on screen, with its paint:

| Format | What you get | Needs Blender? |
|---|---|:---:|
| **`.glb`** | The whole model and its textures in one file. Opens in Blender, Windows 3D Viewer, game engines and more. | ❌ No |
| **`.blend`** | A Blender file made by Blender, with textures packed inside. | ✅ Yes |
| **OBJ (baked textures)** | One mesh with all colours baked into up to 5 textures, and glass kept separate. Texture size 2048, 4096 or 8192, as `.png`, `.tga` or `.tif`. | ✅ Yes |

🖼️ **Screenshot** saves a high-resolution picture of the view at **2× window size, 4K or 8K**, and 🖥️ **Fullscreen** gives a clean look at your truck.

---

## 📸 Screenshots

<details>
<summary><b>Show all screenshots</b></summary>
<br />

| | |
|:---:|:---:|
| <img src="https://i.postimg.cc/rs5CBMDF/render-day.jpg" /> **Render Mode** | <img src="https://i.postimg.cc/wMDcCg1B/render-night.jpg" /> **Night, lights on** |
| <img src="https://i.postimg.cc/63kNRF23/studio.png" /> **Photo studio** | <img src="https://i.postimg.cc/NFR73BKt/dealer.jpg" /> **Truck dealer** |
| <img src="https://i.postimg.cc/2ynFsr1z/paint.jpg" /> **Paint jobs** | <img src="https://i.postimg.cc/x8LywnXf/parts.jpg" /> **Parts and pins** |
| <img src="https://i.postimg.cc/VvXBxmJ1/interior.jpg" /> **Inside the cab** | <img src="https://i.postimg.cc/7LY3MD7x/export-to-game.png" /> **Export to game** |
| <img src="https://i.postimg.cc/0NWpV3dR/import-from-game.png" /> **Import from game** | <img src="https://i.postimg.cc/QxjQsCCb/trailer-dealer.png" /> **Trailer dealer** |
| <img src="https://i.postimg.cc/8PTRDcc4/trailer-set-builder.png" /> **Custom trailer sets** | <img src="https://i.postimg.cc/tR33LWq6/cargo-combination.png" /> **A loaded double** |
| <img src="https://i.postimg.cc/4466rVf9/cargo-list.png" /> **Cargo list** | <img src="https://i.postimg.cc/sD3Yyxx5/cargo-overview.png" /> **Cargo and its details** |
| <img src="https://i.postimg.cc/RVv79hhZ/cargo-machine.png" /> **Machines on a lowbed** | <img src="https://i.postimg.cc/15yGPXXz/cargo-container.png" /> **Containers** |
| <img src="https://i.postimg.cc/gkGVdjjV/lashing-straps.png" /> **Straps and ratchets** | <img src="https://i.postimg.cc/yY7mBxxh/lashing-chains.png" /> **Chains and binders** |
| <img src="https://i.postimg.cc/NfQ6YFFm/hazard-plates.png" /> **Hazard and licence plates** | <img src="https://i.postimg.cc/BvQTcsDG/settings.png" /> **Performance settings** |
| <img src="https://i.postimg.cc/yNYmXB9H/supporters.png" /> **Supporters Wall** | |

</details>

---

## 🧩 Other features and good to know

- ⚡ **Faster loading**: the game's part lists are remembered after the first run, models load on several processor threads at once, and changing one part in the editor updates only that part.
- ⚙️ **Performance settings**: choose which **graphics card** draws the 3D view (the most powerful one by default) and how many **CPU threads** load models. Settings shows how many your PC has, and starts at 2.
- 🔄 **Automatic updates**, with a **changelog** on the start page.
- 🎮 **Discord Rich Presence** shows what you're working on, with buttons to download the app and [join the Discord server](https://discord.gg/FmYvK2Uxwt).
- 💛 **Supporters Wall** on the start page lists the people who have supported the project, next to a **Support me** button that opens [Buy Me a Coffee](https://buymeacoffee.com/rigworksstudio).
- 🖱️ Resizable side panels, and a dark interface built to keep the focus on the truck.
- 🧩 **Mods aren't supported.** Parts from mods can't be loaded and are listed in the build report instead.
- 🔒 Parts are only available if you own the DLC they come from.

> [!IMPORTANT]
> Always **back up your save** before editing it. The save-edit code is plain text, in the same format save tools use. **Export to game** makes its own backup each time, but a copy of your own is still worth having.

> [!CAUTION]
> We take no responsibility for anyone that creates a save edit that gets them banned from a multiplayer network.

<div align="center">
<br />

**Made for the ETS2 community** 🚛💨

</div>
