# FishMate · 3D Prototype Viewer

Interactive 3D model of the FishMate aquarium monitoring prototype. Open `index.html` in any modern browser — no installation required (an internet connection is needed the first time to fetch Three.js and the fonts from their CDNs).

**Live demo:** https://martinez-kateeurisse.github.io/FishMate-3D-Prototype/

## Usage

| Input | Action |
|---|---|
| Left-click + drag | Orbit |
| Scroll / pinch | Zoom |
| Right-click + drag | Pan |

## Controls

| Toggle | Description |
|---|---|
| Enclosure lid | Lift the foam lid to reveal internal components |
| Water fill | Drain the tank — float sensor drops when water is off |
| Internal parts | Show/hide circuit board components |
| Labels | Toggle component annotations |
| Auto-rotate | Continuous rotation |
| Float casing color | Switch foam between white and black |
| Light mode | Toggle dark/light background theme |
| Reset view | Return to default camera angle |

## Components Modeled

- 20 × 20 × 20 cm acrylic aquarium
- Foam circuit tray (25 × 10 × 7 cm) with ESP32, breadboard, relay, and MOSFETs
- Lower platform (5 cm) with float sensor casing (4 × 4 × 4 cm)
- DFRobot turbidity sensor — cylindrical waterproof probe at waterline
- DS18B20 temperature probe — stainless bullet probe, submerged
- Mini submersible pump — white cylindrical body at tank floor
- Clear waterproof wire sleeves on all sensor cables

## Built With

[Three.js r128](https://threejs.org/) — no build step, fully self-contained HTML file.
