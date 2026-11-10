# ع الدائري — Independent 3D driving game

An unofficial, independently authored browser game inspired by the Egyptian Ring Road driving premise and broad gameplay loop of the public reference. All code, procedural 3D vehicles, scenery, signs and UI are original; this repository does not use the reference game's proprietary source, models, textures, audio or artwork.

## Run locally
```bash
python -m http.server 8080
```
Open http://localhost:8080. Three.js is loaded from jsDelivr.

## Controls
- Desktop: Arrow keys / A-D to change lanes, Up/W to accelerate, Down/S to brake, Space/Esc to pause.
- Mobile: on-screen lane, accelerator, brake, horn and nitro buttons; swipe left/right to change lanes.
- Camera: near, normal, far and cockpit presets from the setup screen.

## Included
- Procedural 3D Egyptian highway scene with roadside buildings, exit signs, overhead structures, barriers, lane markings and lights.
- Six vehicle classes, traffic density, four route themes and five time-of-day lighting presets.
- Shift, free-drive, time-trial and flight-inspired arcade modes.
- Coins, three objectives, radar speed checks, vehicle condition, nitro and collisions.
- Garage with unlockable vehicles and per-vehicle engine, brake, nitro and chassis upgrades.
- Local save for wallet, vehicles, upgrades, level and best distance.
- Installable PWA shell with a service worker and offline caching for the app shell.
- Automated GitHub Actions checks for module syntax and PWA manifest validity.

## Deployment
The GitHub Actions Pages workflow is configured in `.github/workflows/deploy.yml`. GitHub Pages must be available and set to use GitHub Actions in repository settings.
