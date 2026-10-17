<div align="center">

<img src="https://i.postimg.cc/KYFXw84N/taskbar.png" width="120" />

# RigWorks Studio

**BUILD IT. SEE IT. DRIVE IT.**<br />
See your Euro Truck Simulator 2 trucks and trailers in 3D, customise them outside the game, and send them straight back to your save.

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
[![Issues](https://img.shields.io/github/issues/M1sterchamp/RigWorks-Studio?label=open%20issues&color=e67e22)](https://github.com/M1sterchamp/RigWorks-Studio/issues)
[![Stars](https://img.shields.io/github/stars/M1sterchamp/RigWorks-Studio?label=stars&color=f1c40f)](https://github.com/M1sterchamp/RigWorks-Studio/stargazers)

[**⬇️ Download**](https://github.com/M1sterchamp/RigWorks-Studio/releases/latest) · [**✨ Features**](#-features) · [**📸 Screenshots**](#-screenshots) · [**💬 Discord**](https://discord.gg/FmYvK2Uxwt)

<br />

<img src="https://i.postimg.cc/rs5CBMDF/render-day.jpg" width="100%" />

</div>

RigWorks Studio is a Windows app that reads ETS2's own game files and rebuilds trucks and trailers exactly as the game defines them: every cab, chassis, part, paint job, light and interior.

- 🚚 **See your truck from your save** in 3D, in a photo studio or one of the game's own main-menu scenes.
- 🛠️ **Rebuild it** in the Save-Edit Builders: paint, parts, interior, engine and wheels, for trucks and trailers.
- 🎮 **Send it straight to the game** in two clicks, or import the one you're driving.
- 🎨 **Design your own skins** for trucks and trailers and export them as local mods. *(Experimental)*
- 📦 **Export it as a 3D model** for Blender, game engines and other 3D software.

> [!NOTE]
> RigWorks Studio is a fan-made tool. It is not affiliated with or endorsed by SCS Software. You need your own copy of Euro Truck Simulator 2.

## 🚀 Getting started

**You need:** Windows 10 or 11 (64-bit) and Euro Truck Simulator 2. DLCs you own are picked up automatically. **Blender** is optional, only for `.blend` and OBJ exports.

1. **Download** the installer from [Releases](https://github.com/M1sterchamp/RigWorks-Studio/releases/latest) and run it.
2. **Open RigWorks Studio.** It finds ETS2 through Steam and reads the game's archives directly. If it can't, use **Game…** to pick the folder containing `base.scs`.
3. **Pick what you want to do** on the start page.

<p align="center"><img src="https://i.postimg.cc/pTV27jKS/home.png" width="85%" /></p>

## ✨ Features

<details>
<summary><b>🎬 Render Mode</b>: your truck in 3D, with working lights, a photo studio and the game's own scenes</summary>
<br />

Rebuild a truck from your save and look around it. Paste its `vehicle_*_accessory` units or drop in a `.txt` file; add an owned trailer and it's hitched up with its cargo, lashing and plate. You can also browse every truck and trailer model in the game, and click any part for its name, price, icon and game files. A **build report** lists anything that couldn't be shown, such as parts from mods.

**Scene menu**

| Option | What it does |
|---|---|
| 📸 **Studio** | A car photo studio with a curved backdrop, softboxes and a turntable. Choose **Soft**, **Dramatic** or **High key** lights, a **White**, **Grey** or **Black** backdrop, a **glossy floor** and **turntable spin**. |
| 🏞️ **Showcase** | Parks your truck in a 3D scene from the game's main menu (see below). |
| 🖼️ **Background image** | Puts any picture of yours behind the truck. Screenshots include it, and it clears when the app closes. |
| 🪞 **Reflections** | A neutral studio setup or game-style reflections. Chrome always reflects like real chrome. |
| 🌙 **Night** · 🌧️ **Rain** | Working headlight beams in the dark; wet weather *(heavy on the graphics card)*. |
| 📐 **Grid** · 📍 **Attachment points** · 🚛 **Trailer** | Floor grid, the game's mount points, and show or hide the trailer. |

**🏞️ Showcase scenes** are the 3D sets from the game's own main menu, loaded from your game files with their lighting, baked shadows, reflections and animations: **Home at Last**, **Under the Bridge**, **Northern Lights**, **On Top of the World**, **Magic Time** and **Black Light Studio**.

| | |
|:---:|:---:|
| <img src="https://i.postimg.cc/d1WqK094/showcase-garage.png" /> **Home at Last** | <img src="https://i.postimg.cc/FRP9QKxW/showcase-northern-lights.png" /> **Northern Lights** |
| <img src="https://i.postimg.cc/85y1VCb4/showcase-bridge.png" /> **Under the Bridge** | <img src="https://i.postimg.cc/qRBkYK29/showcase-magic-time.png" /> **Magic Time** |

**💡 Working lights and animation**: headlights, high beams, tail and marker lights, rotating **beacons** and double-flash **strobes**, **brake lights**, **indicators** and hazards, the game's own **wiper** animations, and **turning wheels**.

</details>

<details>
<summary><b>🛠️ Truck Save-Edit Builder</b>: paint, parts, interiors, engines and wheels</summary>
<br />

Start from any dealer truck in the game (browse by brand or search, e.g. `FH6 globetrotter 6x2`, and pick a chassis), or import your own from a code, a `.txt` file or straight from your save with **Import from game…**.

- 🎨 **Paint**: every paint job that fits the cab, sorted into **Colours**, **Metallic** and **Designs**, with a live colour editor where the paint allows it. Metallic paint has a clean, glossy flake finish.
- 🔧 **Parts**: click the pins on the truck to swap, fit or remove a part. Pins sit on the real part, cover both sides of paired parts and every light slot, and hide with <kbd>P</kbd>.
  - The **part picker** lists parts made for your truck first. **Show all** adds parts that may not fit (marked ⚠️ with why), and **Other truck brands** borrows parts from other trucks.
  - ➕ **Add as an extra part** stacks a second part on the same pin. Only the part you picked is added, not the extras another truck would bring with it.
  - 💡 Fit any light in the game to a light slot, and 🖌️ paint individual parts, with ⭐ favourite colours.
- 🛞 **Wheels**: a change goes on both wheels of the axle; tick **Change every axle** and rims, hubs, nuts, covers and their paint go on every wheel. Hubs, nuts and covers follow the rim's offset, and only matching ones are listed.
- 🪑 **Interior tab**: every interior for the cab, left- or right-hand drive, with prices. Picking one moves the view inside and shows it in full detail.
- ⚙️ **Core parts and performance**: change the chassis, cab, engine, transmission and headlights, from this truck or others. The **Performance** panel draws the engine's torque and power curves and shows horsepower, torque band, displacement, gears, retarder, final drive, engine speed at 85 km/h and top-gear speed.
- 🤝 What the game adds automatically is added for you (for example, camera mirrors bring their cab screens).
- ↩️ **Undo** (<kbd>Ctrl</kbd> + <kbd>Z</kbd>) for every change, and **Save-edit code…** to copy or save the whole truck for **Project-ALM** and other save editors.

<table><tr>
<td><img src="https://i.postimg.cc/HxWpKMbK/interior.png" /><p align="center"><b>Interior tab</b></p></td>
<td><img src="https://i.postimg.cc/pT02tdBk/performance.png" /><p align="center"><b>Engine performance</b></p></td>
</tr></table>

</details>

<details>
<summary><b>🎮 Export to game and import from game</b>: no copying and pasting</summary>
<br />

1. Build your truck or trailer, then click **Export to game…**.
2. Pick the **profile** and **save**, listed by the names you see in game.
3. Click **Export to game**, then load that save in ETS2.

**Import from game…** in the truck or trailer dealer does the reverse: it loads the truck you're driving, or the trailer hooked to it, with its paint, parts and plate. Importing only reads the save.

- 💾 **A backup is made first**, every time. **Show backup** opens it, and the last 10 backups of each save are kept.
- 🎮 If the game is open, load the save from its menu after exporting, and don't save over it from the running game.
- 📁 Profiles are found in `Documents\Euro Truck Simulator 2` (local and Steam Cloud). If yours are elsewhere, set **Settings → ETS2 profiles folder**.

> [!WARNING]
> Exporting **replaces your currently active vehicle** in that save: a truck replaces the truck you're driving, and a trailer replaces the trailer hooked to it (and any behind it).

<p align="center"><img src="https://i.postimg.cc/7LY3MD7x/export-to-game.png" width="85%" /></p>

</details>

<details>
<summary><b>🚚 Trailers and cargo</b>: doubles, B-doubles, custom sets, loads, lashing and plates</summary>
<br />

The **Trailer Save-Edit Builder** works like the truck one: pick an owned trailer at the dealers or import yours, change its paint and parts, load it, and export it or take the code.

- 🔗 **Combinations**: single, **double**, **B-double** or **HCT**, as the game's trailer shop offers them. Switch between **Trailer 1 · Dolly · Trailer 2** to edit each unit.
- 🧩 **Build custom set…** hitches trailers and dollies of any make together, up to **B-triples** and **drawbar triples**, with a preview of each trailer as you hover over it. Each unit is checked against the coupling in front. *(Not sold by the game's shop, so at your own risk.)*
- 📦 **Cargo**: the green pin opens every load the game can show, each with a picture. Choose how many, **Copy to all** trailers, and tick **Real weight** to make it count in game. Select one for its mass, volume, pay rate, ADR class and more.
- ⛓️ **Lashing** with the game's own straps, chains, ratchets, binders and hooks, plus tie-down rings on lowbeds.
- 🔖 **Licence plates** on every trailer (`AB12 CDE|uk`), and **ADR plates and diamonds** on dangerous goods.
- 📋 The **save-edit code** has one linked unit per trailer or dolly; give it your trailer's ID and `trailer_definition` and it slots straight into `game.sii`.

<p align="center"><img src="https://i.postimg.cc/tR33LWq6/cargo-combination.png" width="85%" /></p>

</details>

<details>
<summary><b>🎨 Truck and Trailer Skin Makers</b> <i>(Experimental)</i>: design skins and export them as local mods</summary>
<br />

Design a skin on the game's own template for a truck or trailer, with a live 3D preview, and export it as a zipped local mod.

- 🖌️ Layers of **images**, **text**, **gradients** and **shapes** (stripes and more) over a background colour, with snapping, zoom, undo and redo.
- 🧭 The **template** shows where each part of the vehicle sits, labelled front, back, left and right; a **test pattern** checks how it wraps.
- 🚚 **Truck skins** cover the cab and the chassis parts; **trailer skins** cover the body.
- 💾 **Save design…** and **Open…** to keep working later, **Export skin image…** for the texture alone, or **Export local mod…** for a mod ready to drop into your `mod` folder.

> [!CAUTION]
> Local modding is **highly experimental** and may be removed in a future update if it causes too many issues.

<p align="center"><img src="https://i.postimg.cc/DZf2DG1M/skin-maker.png" width="85%" /></p>

</details>

<details>
<summary><b>📦 Exporting 3D models and pictures</b></summary>
<br />

| Format | What you get | Needs Blender? |
|---|---|:---:|
| **`.glb`** | The whole model and its textures in one file, for Blender, Windows 3D Viewer, game engines and more. | ❌ |
| **`.blend`** | A Blender file with textures packed inside. | ✅ |
| **OBJ (baked textures)** | One mesh with all colours baked into up to 5 textures (2048–8192, `.png`, `.tga` or `.tif`), glass kept separate. | ✅ |

🖼️ **Screenshot** saves the view at **2× window size, 4K or 8K**, including any background image or showcase scene, and 🖥️ **Fullscreen** gives a clean look at your truck.

</details>

<details>
<summary><b>🧩 Other features and good to know</b></summary>
<br />

- ⚡ **Fast loading**: part lists are remembered after the first run, models load on several CPU threads, and changing one part only rebuilds that part.
- ⚙️ **Performance settings**: choose the **graphics card** for the 3D view and how many **CPU threads** load models.
- 🔄 **Automatic updates**, with a **changelog** on the start page.
- 🎮 **Discord Rich Presence** shows what you're working on.
- 💛 **Supporters Wall** on the start page, next to a **Support me** button for [Buy Me a Coffee](https://buymeacoffee.com/rigworksstudio).
- 🧩 **Mods aren't supported** in the builders: their parts are listed in the build report instead. Parts are only available from DLCs you own.

</details>

## 📸 Screenshots

<details>
<summary><b>Show all screenshots</b></summary>
<br />

| | |
|:---:|:---:|
| <img src="https://i.postimg.cc/rs5CBMDF/render-day.jpg" /> **Render Mode** | <img src="https://i.postimg.cc/wMDcCg1B/render-night.jpg" /> **Night, lights on** |
| <img src="https://i.postimg.cc/63kNRF23/studio.png" /> **Photo studio** | <img src="https://i.postimg.cc/d1WqK094/showcase-garage.png" /> **Showcase: Home at Last** |
| <img src="https://i.postimg.cc/NFR73BKt/dealer.jpg" /> **Truck dealer** | <img src="https://i.postimg.cc/2ynFsr1z/paint.jpg" /> **Paint jobs** |
| <img src="https://i.postimg.cc/x8LywnXf/parts.jpg" /> **Parts and pins** | <img src="https://i.postimg.cc/LX4H7Pj0/chrome.png" /> **Chrome parts** |
| <img src="https://i.postimg.cc/HxWpKMbK/interior.png" /> **Interior tab** | <img src="https://i.postimg.cc/pT02tdBk/performance.png" /> **Engine performance** |
| <img src="https://i.postimg.cc/VvXBxmJ1/interior.jpg" /> **Inside the cab** | <img src="https://i.postimg.cc/DZf2DG1M/skin-maker.png" /> **Truck Skin Maker** |
| <img src="https://i.postimg.cc/7LY3MD7x/export-to-game.png" /> **Export to game** | <img src="https://i.postimg.cc/0NWpV3dR/import-from-game.png" /> **Import from game** |
| <img src="https://i.postimg.cc/QxjQsCCb/trailer-dealer.png" /> **Trailer dealer** | <img src="https://i.postimg.cc/8PTRDcc4/trailer-set-builder.png" /> **Custom trailer sets** |
| <img src="https://i.postimg.cc/tR33LWq6/cargo-combination.png" /> **A loaded double** | <img src="https://i.postimg.cc/sD3Yyxx5/cargo-overview.png" /> **Cargo and its details** |
| <img src="https://i.postimg.cc/RVv79hhZ/cargo-machine.png" /> **Machines on a lowbed** | <img src="https://i.postimg.cc/15yGPXXz/cargo-container.png" /> **Containers** |
| <img src="https://i.postimg.cc/gkGVdjjV/lashing-straps.png" /> **Straps and ratchets** | <img src="https://i.postimg.cc/yY7mBxxh/lashing-chains.png" /> **Chains and binders** |
| <img src="https://i.postimg.cc/NfQ6YFFm/hazard-plates.png" /> **Hazard and licence plates** | <img src="https://i.postimg.cc/BvQTcsDG/settings.png" /> **Performance settings** |

</details>

> [!IMPORTANT]
> Always **back up your save** before editing it. **Export to game** makes its own backup each time, but a copy of your own is still worth having.

> [!CAUTION]
> We take no responsibility for anyone whose save edit gets them banned from a multiplayer network.

<div align="center">
<br />

**Made for the ETS2 community** 🚛💨

</div>
