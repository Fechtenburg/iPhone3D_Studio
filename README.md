# Premium 3D App Store Screenshot Studio

A high-performance, interactive 3D web application to generate stunning App Store screenshots and marketing assets. Supports iPhone and iPad Pro 13". Built with HTML, CSS, and **Three.js** — runs locally in your browser.

## Features

- **Dual Device Support:** Toggle between iPhone and iPad Pro 13" with per-device geometry, camera bump, and presets.
- **Drag-and-Drop Texturing:** Instantly wrap app screenshots onto the 3D model by dropping an image onto the browser window.
- **Precision Camera Control:** Intuitive sliders for X/Y/Z rotation and studio zoom scale.
- **Dynamic Studio Presets:** Store, rename, and recall up to 8 camera angles per device (separate localStorage keys).
- **Transparent PNG Export:** Capture crisp transparent `.png` renders with one click.
- **Advanced Physical Materials:** `MeshPhysicalMaterial` with clearcoat, metalness, and roughness matching titanium/aluminum edges and back glass.
- **Detailed Hardware:** Optical lens simulation with light transmission, Dynamic Island (iPhone), speaker grilles, side buttons, Apple logo with leaf geometry.
- **Photorealistic Lighting:** Directional studio lighting, HDR tone mapping, PCFSoftShadowMap.
- **No Installation Required:** Open in any modern browser.

## How to Use

1. Open `iOS.html` in any modern browser.
2. Click **iPhone** or **iPad** to switch devices.
3. Drag and drop a screenshot onto the device screen.
4. Use mouse to orbit, or fine-tune angle with **Canvas Transformation** sliders.
5. Save favorite angles with **Dynamic Studio Presets**.
6. Click **Capture Transparent PNG** to export.

## Tech Stack

- **HTML5 / CSS3** — Glassmorphism UI
- **Three.js** (r128) — WebGL 3D engine
- **OrbitControls** — Camera interaction

## License

MIT