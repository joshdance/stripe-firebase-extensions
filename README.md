# Gem Dropping Game

A simple Three.js game where you drop colorful gems and watch them pile up with realistic physics and satisfying tinkle sounds.

## How to Play

1. Open `index.html` in a web browser
2. Press keyboard keys to spawn gems:
   - **A** - Drop a red gem
   - **B** - Drop a green gem
   - **C** - Drop a purple gem

## Features

- 3D rendered gems using Three.js
- Realistic physics simulation (gravity, bouncing, gem-to-gem collisions)
- Procedurally generated crystal tinkle sounds on impact
- Gems pile up naturally at the bottom
- Beautiful lighting with shadows and glow effects

## Running the Game

Simply open the `index.html` file in any modern web browser. No build step or server required - everything runs client-side using ES modules from CDN.

```bash
# Option 1: Open directly
open index.html

# Option 2: Use a local server (for development)
python -m http.server 8000
# Then visit http://localhost:8000
```

## Technologies Used

- Three.js - 3D rendering
- Web Audio API - Procedural sound generation
- Custom physics engine - Collision detection and response
