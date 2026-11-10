# ع الدائري — Independent 3D driving game

An unofficial, independently authored browser game inspired by the Egyptian Ring Road driving premise. All source code, procedural 3D vehicles, scenery and UI are original; this project does not use the reference game's proprietary source, models, textures, audio or artwork.

## Run locally
```bash
python -m http.server 8080
```
Open http://localhost:8080. Three.js is loaded from jsDelivr.

## Controls
- Desktop: Arrow keys / A-D to change lanes, Up/W to accelerate, Down/S to brake, Space/Esc to pause.
- Mobile: on-screen lane, accelerator, brake, horn and nitro buttons; swipe left/right to change lanes.

## Included
- Procedural 3D highway, roadside buildings, barriers, lane markings and lights.
- Six vehicle classes, traffic density, four route themes and five lighting presets.
- Shift, free-drive, time-trial and flight-inspired arcade modes.
- Coins, objectives, radar speed checks, vehicle condition, nitro and collisions.
- Garage with unlockable vehicles and per-vehicle engine, brake, nitro and chassis upgrades.
- Local save for wallet, vehicles, upgrades, level and best distance.
- Responsive Arabic UI and touch controls.

## Deployment
GitHub Actions deploys the static site to Pages when the repository Pages source is set to GitHub Actions.
