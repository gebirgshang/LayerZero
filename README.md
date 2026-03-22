# 🖨️ LAYER ZERO

### 3D Print Farm Simulator

> *“Every print farm empire started with one janky printer on a desk, some tangled filament, and an unhealthy amount of caffeine.”*

-----

**Layer Zero** is a fully interactive 3D print farm management game built entirely in the browser using **Three.js**. Start with a single printer on a cozy desk, fulfill orders, manage filament, and grow your operation from a tiny nook into a full-scale print depot.

🎮 **[Play Now → gebirgshang.github.io/LayerZero](https://gebirgshang.github.io/LayerZero/)**

-----

## 🎯 Gameplay

You run a 3D print farm. Your job is to manage the entire pipeline:

1. **Buy filament** from the shop — PLA, PETG, ABS, Carbon Fiber in various colors
1. **Load filament** into your printers — each printer needs a spool loaded before it can work
1. **Accept orders** from clients — match the right filament to the right job
1. **Assign orders** to loaded printers and watch them print
1. **Ship deliveries** — collect finished prints and ship them from the delivery box to earn cash
1. **Upgrade** — buy more printers, unlock speed boosts, and level up your workspace

## 🏭 Three Levels

|Level|Name          |Max Printers|Vibe                                         |
|-----|--------------|------------|---------------------------------------------|
|1    |**The Nook**  |4           |Cozy desk corner with string lights and books|
|2    |**The Garage**|8           |Steel workbench, pegboard, garage door       |
|3    |**The Depot** |12          |Industrial warehouse with server racks       |

## ✨ Features

- **First-person 3D view** — look around your room, tap printers and objects to interact
- **Full print farm simulation** — orders, filament management, printer loading, delivery system
- **In-game computer (CMD Center)** — dashboard, order management, printer control, shop, upgrades
- **Sound effects** — satisfying tones for buying, printing, completing orders, achievements
- **Achievement system** — unlock milestones as you grow your empire
- **Funny dialogue** — Print-Bot 3000, Filament Fairy, Spaghetti Monster, and more drop commentary
- **GLB model support** — replace any object with custom 3D models
- **Touch-friendly** — built for iPad and mobile, drag to look, tap to interact
- **Single HTML file** — no build step, no dependencies, just open and play

## 🎨 Custom 3D Models

Drop `.glb` files into the `Models/` folder to replace primitive objects:

|Filename     |Replaces               |
|-------------|-----------------------|
|`plant.glb`  |Potted plant on desk   |
|`printer.glb`|3D printer             |
|`desk.glb`   |L-shaped desk          |
|`spool.glb`  |Filament spool on shelf|
|`monitor.glb`|Computer monitor       |
|`mug.glb`    |Coffee mug             |
|`lamp.glb`   |Desk lamp              |
|`chair.glb`  |Stool/chair            |
|`box.glb`    |Delivery box           |
|`clock.glb`  |Wall clock             |

Adjust scale and position in `MODEL_CONFIG` at the top of the script in `index.html`.

## 🛠️ Tech Stack

- **Three.js** (r128) — 3D rendering
- **Web Audio API** — procedural sound effects
- **GLTFLoader** — custom 3D model support
- **Vanilla JS** — no frameworks, no build tools
- **Single file** — entire game in one `index.html`

## 📁 Project Structure

```
LayerZero/
├── index.html          # The entire game
├── Models/             # Custom 3D models (optional)
│   ├── plant.glb
│   ├── mug.glb
│   ├── clock.glb
│   ├── spool.glb
│   └── box.glb
└── README.md
```

## 🚀 Run Locally

No setup needed. Just:

```bash
git clone https://github.com/gebirgshang/LayerZero.git
cd LayerZero
# Open index.html in any browser, or use a local server:
npx serve .
```

## 📜 License

**© 2025 gebirgshang.eth — All Rights Reserved.**

This project is proprietary. No permission is granted to copy, modify, distribute, remix, fork, or use any part of this project for commercial or non-commercial purposes without explicit written permission from the creator. Viewing the live demo is permitted. All other rights are reserved.

-----

<div align="center">

### Created by **gebirgshang.eth**

*Game Design • Development • Art Direction*

Built with ☕ and way too much filament.

</div>
