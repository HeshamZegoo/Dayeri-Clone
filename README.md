# Dayeri Clone — prototype

An independent browser-based 3D driving game inspired by the Cairo Ring Road setting and broad gameplay loop of the reference game. It does not use the original game's source code, models, textures, audio, or branding assets.

## Run locally
Open `index.html` in a modern browser with internet access (Three.js is loaded from jsDelivr). For best results use a local static server:

```bash
python -m http.server 8080
```

Then visit http://localhost:8080.

## Controls
- Desktop: Arrow keys or A/D to change lanes; W/Up to accelerate; S/Down to brake; Space/Esc to pause.
- Mobile: on-screen left/right, accelerator and brake buttons; swipe left/right on the scene to change lanes.

## Current prototype
- Procedural 3D road, roadside buildings, barriers, lane markings and traffic vehicles.
- Selectable player vehicle, traffic density and time of day.
- Speed, distance, collision and best-distance tracking (local browser storage).
- Responsive touch controls.

## Roadmap
Improve handling/physics, add more authentic Cairo road scenery and vehicle variety, garage upgrades, radio/audio, missions, and mobile performance testing.
