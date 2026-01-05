# P.ASC.II - 3D ASCII Pacman

A 3D Pacman game rendered entirely in ASCII characters using Three.js AsciiEffect.

## Features

- **TRUE ASCII Rendering**: The entire game is rendered as actual text characters via Three.js AsciiEffect
- **Retro Aesthetic**: Green-on-black color scheme with phosphor glow effects
- **3D Amsterdam Cityscape**: Canal houses, church tower, and bridges surround the maze
- **Cinematic Camera Director**: 5 dramatic camera modes cycle in demo mode:
  - ASCII Reveal: Far zoom showing the entire scene is made of ASCII
  - Extreme ASCII: Super close-up to see individual characters
  - Wall Flyover: Low flying over the maze walls
  - City Orbit: Wide orbit showing the Amsterdam skyline
  - Action Follow: Dynamic follow shot of Pacman
- **Spatial Audio**: Directional ghost sounds and ambient music
- **Classic Gameplay**: Collect dots, avoid ghosts, eat power pellets to hunt ghosts

## How to Play

1. Open `pacman.html` in a web browser
2. Press SPACE to start the game
3. Use arrow keys to move Pacman
4. Collect all dots to win
5. Avoid ghosts (or eat them when they're blue after a power pellet)

## Controls

- **Arrow Keys**: Move Pacman
- **SPACE**: Start game / Restart after game over
- **M**: Toggle music

## Technical Details

Built with:
- Three.js for 3D rendering
- AsciiEffect for true ASCII output
- Web Audio API for spatial sound
- Pure vanilla JavaScript (no build step required)

## Running Locally

Simply serve the directory with any HTTP server:

```bash
# Python 3
python -m http.server 8888

# Node.js
npx serve .

# PHP
php -S localhost:8888
```

Then open `http://localhost:8888/pacman.html` in your browser.

## License

MIT
