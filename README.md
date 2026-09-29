<div align="center">

<img src="https://i.postimg.cc/KYFXw84N/taskbar.png" width="120" />

# RigWorks Studio

**See your Euro Truck Simulator 2 trucks in 3D, customise them outside the game, and export them.**

[![Latest release](https://img.shields.io/github/v/release/M1sterchamp/RigWorks-Studio?include_prereleases&label=version&color=4f7cff&style=for-the-badge)](https://github.com/M1sterchamp/RigWorks-Studio/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/M1sterchamp/RigWorks-Studio/total?color=2ea44f&style=for-the-badge)](https://github.com/M1sterchamp/RigWorks-Studio/releases)
![Status: beta](https://img.shields.io/badge/status-beta-f0883e?style=for-the-badge)

![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white)
![Euro Truck Simulator 2](https://img.shields.io/badge/Euro%20Truck%20Simulator%202-supported-e8a33d)
![Electron](https://img.shields.io/badge/Electron-44-47848F?logo=electron&logoColor=white)
![three.js](https://img.shields.io/badge/three.js-r186-222222?logo=threedotjs&logoColor=white)
![Blender export](https://img.shields.io/badge/Blender-export-E87D0D?logo=blender&logoColor=white)
![Discord Rich Presence](https://img.shields.io/badge/Discord-Rich%20Presence-5865F2?logo=discord&logoColor=white)

[**⬇️ Download**](https://github.com/M1sterchamp/RigWorks-Studio/releases/latest) · [**✨ Features**](#-render-mode) · [**📸 Screenshots**](#-screenshots) 

<br />

<img src="https://i.postimg.cc/rs5CBMDF/render-day.jpg" width="100%" />

</div>

RigWorks Studio is a Windows desktop app that reads ETS2's own game files and rebuilds trucks and trailers exactly as the game defines them: every cab, chassis, accessory, paint job, light and interior.

- 🚚 **Look at your truck from your save** in 3D, day or night, with working lights.
- 🛠️ **Plan a build in the Save Edit Builder** and get a save-edit code for Project-ALM and other save tools.
- 📦 **Export it as a 3D model** for Blender, game engines and other 3D software.

> [!NOTE]
> RigWorks Studio is a fan-made tool. It is not affiliated with or endorsed by SCS Software. You need your own copy of Euro Truck Simulator 2.

---

## 📋 Contents

- [✅ Requirements](#-requirements)
- [🚀 Getting started](#-getting-started)
- [🎬 Render Mode](#-render-mode)
- [🛠️ Save Edit Builder](#️-save-edit-builder)
- [📦 Exporting 3D models](#-exporting-3d-models)
- [📸 Screenshots](#-screenshots)
- [🧩 Other features](#-other-features)
- [💡 Good to know](#-good-to-know)

---

## ✅ Requirements

| | Requirement | Notes |
|---|---|---|
| 🪟 | **Windows 10 or 11** | 64-bit |
| 🚛 | **Euro Truck Simulator 2** | Steam or other installs. DLCs you own are picked up automatically. |
| 🎨 | **Blender** *(optional)* | Only for `.blend` and OBJ exports. The `.glb` export works without it. |

## 🚀 Getting started

1. **Download** the latest installer from the [Releases](https://github.com/M1sterchamp/RigWorks-Studio/releases/latest) page and run it.
2. **Open RigWorks Studio.** It finds your ETS2 install through Steam automatically. If it can't, use **Game…** to point it at the game folder.
3. **Choose a mode** on the start page:
   - 🎬 **Render Mode**: build a truck from your save, look around it, screenshot it or export it.
   - 🛠️ **Save Edit Builder**: start from a dealer truck (or import your own), change its paint and parts, and get a save-edit code.

> [!TIP]
> The app reads the game's archives directly. There's nothing to extract or unpack.

<p align="center">
  <img src="https://i.postimg.cc/5y8qhbXV/home.jpg" width="85%" />
</p>

---

## 🎬 Render Mode

### 🧾 Build your truck from your save
- Paste a truck's `vehicle_*_accessory` units from your save file, or **import a `.txt` file** (drag and drop works too), and the truck is rebuilt with every part in place.
- Add an **owned trailer** as well and it is hitched to the fifth wheel.
- 🔖 **Licence plates** are shown with your plate text, either typed in or read from the save's `license_plate` line.
- A **build report** lists any part that couldn't be shown, such as parts from mods or DLCs you don't have.

### 🔍 Browse the game's models
- Search every truck and trailer model in the game and your DLCs, and view each one on its own.
- Switch between each model's **looks** and **variants**.
- Click any part to see its name, category, price, icon and the game files it comes from.

### 🌗 Scene options
| Option | What it does |
|---|---|
| 🪞 **Reflections** | A neutral studio setup, or game-style reflections |
| 🌙 **Night** | Dark scene with working headlight beams lighting up the ground |
| 🌧️ **Rain** | Wet weather *(heavy on the graphics card)* |
| 📐 **Grid** | A floor grid under the truck |
| 📍 **Attachment points** | The game's mount locators |
| 🚛 **Trailer** | Show or hide the hitched trailer |

### 💡 Working lights and animation
| Toggle | What lights up or moves |
|---|---|
| **Lights** | Headlights, high beams, red tail lights, roof and aux lights, marker lights and decorative lights |
| **Beacons** | Rotating beacons pulse, and LED strobes flash in a real double-flash pattern |
| **Brake lights** | The brake lamps |
| **Indicators** | Left, right or hazards, on the head and tail lamps only |
| **Wipers** | Animated with the game's own animations, including the mirrored UK-cab versions |
| **Wheels turning** | The wheels spin as if the truck is driving |

<p align="center">
  <img src="https://i.postimg.cc/wMDcCg1B/render-night.jpg" width="85%" />
</p>

---

## 🛠️ Save Edit Builder

Design a truck from any dealer configuration in the game, then take it into your save with a save-edit code.

### 🏪 Pick a base truck
- Browse every **dealer truck** by brand, or search (e.g. `FH6 globetrotter 6x2`).
- Pick a different **chassis** before you start. Parts that don't suit it are swapped for ones that do.
- Or 📥 **import your own truck**: paste its units from Project-ALM or another save tool, or open a `.txt` file.

<p align="center">
  <img src="https://i.postimg.cc/NFR73BKt/dealer.jpg" width="85%" />
</p>

### 🎨 Paint
- Every paint job that fits the cab, sorted into **Colours**, **Metallic** and **Designs**, with search.
- Change the colours of paint jobs that allow it (base colour and colours 1–3), with a live preview on the truck.

<p align="center">
  <img src="https://i.postimg.cc/2ynFsr1z/paint.jpg" width="85%" />
</p>

### 🔧 Parts
- 📍 **Click-to-edit pins** on the truck show every place a part can go. Click one to swap the part, fit a new one, or remove it.
  - Pins sit on the actual part. Parts that come in pairs (mirrors, sideskirts, fenders, steps, lights) get a pin on each side.
  - Empty slots show where a part *would* go before you fit one.
  - Wheel pins on every axle, and small pins for each **light slot** on parts like light bars and bull bars.
  - 👁️ **Hide or show the pins** at any time with the button in the view or the <kbd>P</kbd> key.
- 🪑 **Inside the cab**: switch to the interior view to add or change dashboard sets, bed and seat items, hanging toys, curtains, windshield sets, steering wheels and more. The camera sits at the driver's head position and looks around from there.
- 🗂️ **Part picker**: parts made for your truck are listed first, with price and icon.
  - **Show all** lists parts that may not fit, clearly marked with a ⚠️ and the reason (for example, "made for the high sleeper cab").
  - **Other truck brands** lets you borrow the same kind of part from another truck.
  - ➕ **Add as an extra part** stacks a second part on the same pin, a common save-editing trick. Each copy gets its own pin and can be changed or removed separately.
- 💡 **Lights on accessories**: fit lights to light slots from the game's full range. Lights made for that spot are listed first, then other lights, then everything else.
- ⚙️ **Core parts**: change the **chassis, cab, engine, transmission, headlights and interior**, including options from other trucks.
- 🤝 Things the game does automatically are handled for you. For example, fitting digital camera mirrors also adds their screens inside the cab.
- 🖌️ **Paint individual parts** that can be painted, with a colour picker and a reset to the part's own colour.
- ⭐ **Favourite colours**: save colours you use often. A palette appears in the view whenever a paintable part is selected.
- ⚠️ Warnings when a part may not work in game, and a **⚠ Remove** button for parts the truck needs.
- ↩️ **Undo** (<kbd>Ctrl</kbd> + <kbd>Z</kbd>) for every change, and a searchable list of every part on the truck.

<p align="center">
  <img src="https://i.postimg.cc/x8LywnXf/parts.jpg" width="49%" />
  <img src="https://i.postimg.cc/VvXBxmJ1/interior.jpg" width="49%" />
</p>

### 📋 Get your save-edit code
- **Save-edit code…** gives you the whole truck as save units, ready to paste into **Project-ALM** or another save editor.
- 📋 **Copy** it to the clipboard or 💾 **save it as a `.txt` file**.

---

## 📦 Exporting 3D models

Save what's on screen, with its current look, variant and paint:

| Format | What you get | Needs Blender? |
|---|---|:---:|
| **`.glb`** | The whole model and its textures in one file. Opens in Blender, Windows 3D Viewer, game engines and more. | ❌ No |
| **`.blend`** | A Blender file made by Blender, with textures packed inside. | ✅ Yes |
| **OBJ (baked textures)** | One mesh with all colours baked into up to 5 textures, and glass kept separate. Texture size 2048, 4096 or 8192, as `.png`, `.tga` or `.tif`. | ✅ Yes |

### 🖼️ Screenshots of your truck
- Save a high-resolution picture of the view at **2× window size, 4K or 8K**.
- 🖥️ **Fullscreen** view for a clean look at your truck.

---

## 📸 Screenshots

| | |
|:---:|:---:|
| <img src="https://i.postimg.cc/rs5CBMDF/render-day.jpg" /> **Render Mode** | <img src="https://i.postimg.cc/wMDcCg1B/render-night.jpg" /> **Night, lights on** |
| <img src="https://i.postimg.cc/NFR73BKt/dealer.jpg" /> **Truck dealer** | <img src="https://i.postimg.cc/2ynFsr1z/paint.jpg"/> **Paint jobs** |
| <img src="https://i.postimg.cc/x8LywnXf/parts.jpg" /> **Parts and pins** | <img src="https://i.postimg.cc/x8LywnXf/parts.jpg" /> **Inside the cab** |

---

## 🧩 Other features

- 🔄 **Automatic updates**: the app tells you when a new version is ready and installs it on restart.
- 🎮 **Discord Rich Presence**: shows what you're working on in your Discord status.
- 📰 **Changelog** on the start page, so you can see what's new.
- 🖱️ Resizable side panels, and a dark interface built to keep the focus on the truck.

---


## 💡 Good to know

> [!IMPORTANT]
> Always **back up your save** before editing it. The save-edit code is plain text, in the same format save tools use.

- 🧩 **Mods aren't supported.** Parts from mods can't be loaded and are listed in the build report instead.
- 🔒 Parts are only available if you own the DLC they come from.
- 📁 If the app can't find the game, use **Game…** to choose your Euro Truck Simulator 2 folder (the one containing `base.scs` and `def.scs`).

<div align="center">
<br />

**Made for the ETS2 community** 🚛💨

</div>
