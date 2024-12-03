# River Raid Game

A modern browser-based implementation of the classic River Raid game, inspired by the Atari 2600 version.

## How to Play Locally

1. Clone this repository:
```bash
git clone https://github.com/yazeedaly/river-raid-js.git
cd river-raid-js
```

2. Open index.html in your web browser
   - You can double-click the file
   - Or use a local server (recommended)
   
   Using Python to create a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Then open http://localhost:8000 in your browser
   ```

## Game Controls

- **←/→ Arrow Keys**: Move left/right
- **Space Bar**: Shoot
- **F Key**: Refuel when over a fuel depot (green)

## Gameplay

- Guide your aircraft down the river
- Shoot enemy aircraft and ships for points
- Collect fuel from green fuel depots
- Avoid running out of fuel
- Avoid colliding with enemies or the river banks

## Features

- Classic River Raid gameplay mechanics
- Score tracking system
- Fuel management
- Progressive difficulty
- Sound effects
- Responsive controls

## Development

This game is built using:
- HTML5 Canvas for rendering
- Vanilla JavaScript for game logic
- CSS for styling

## License

This project is open source and available under the MIT License.