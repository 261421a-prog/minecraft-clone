# Minecraft Clone v2.0

A browser-based Minecraft-like voxel game with inventory, crafting, and a server browser — built with Three.js. No install needed, just open `index.html`!

## Controls

| Key | Action |
|-----|--------|
| `WASD` | Move |
| `Space` | Jump |
| `Mouse` | Look around |
| `Left Click` | Break block (adds to inventory!) |
| `Right Click` | Place block (uses from hotbar) |
| `1–6` | Select hotbar slot |
| `E` | Open Inventory & Crafting |
| `Esc` | Open Game Menu |

## Features

### Inventory
- 27-slot inventory + 6-slot hotbar
- Click a slot to pick it up, click another to swap
- Breaking blocks automatically adds them to your inventory
- Placing blocks uses them from your hotbar

### Crafting (2x2 grid)
| Recipe | Result |
|--------|--------|
| 4x Wood | 4 Planks |
| 4x Plank | 4 Glass |
| 2x Stone (left column) | 4 Brick |
| 2x Dirt (top row) | 1 Grass |
| 1x Wood | 2 Coal |

### Server Browser
- Browse simulated multiplayer servers with ping & player counts
- Direct connect input field
- Refresh pings

## How to Run

1. Clone or download this repo
2. Open `index.html` in your browser — done!

> No npm, no build step. Three.js loads from CDN.

## Host Free on GitHub Pages

1. Push to GitHub
2. Settings → Pages → Branch: `main`, folder: `/root`
3. Save → live at `https://YOUR_USERNAME.github.io/minecraft-clone`

## Built With

- [Three.js r128](https://threejs.org/) — 3D rendering
- Vanilla JS — game logic, physics, UI
- HTML5 Pointer Lock API — mouse look

## License
MIT
