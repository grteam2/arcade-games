# 🎮 Classic Arcade Games Collection

A collection of 11 classic arcade games built with HTML5 Canvas and JavaScript. Play all your favorite retro games directly in your browser!

## 🕹️ Games Included

1. **Tetris** - Classic block-stacking puzzle game
2. **Pac-Man** - Navigate mazes, eat dots, avoid ghosts
3. **Snake** - Guide the snake to eat food and grow
4. **Pong** - The original video game - table tennis
5. **Breakout** - Break bricks with a bouncing ball
6. **Space Invaders** - Defend Earth from alien invasion
7. **Asteroids** - Destroy asteroids in space
8. **Galaxian** - Fight off diving alien fleets
9. **Frogger** - Help the frog cross roads and rivers
10. **Donkey Kong** - Rescue Pauline from the giant ape
11. **Centipede** - Shoot the centipede before it reaches you

## 🚀 Quick Start

1. Open `launcher.html` in your web browser
2. Click on any game to start playing
3. Use the controls shown on each game screen
4. Press `P` to pause any game

## 📋 Requirements

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required - runs entirely in the browser
- JavaScript enabled

## 🎮 How to Play

### Option 1: Direct File Access
Simply open `launcher.html` in your web browser.

### Option 2: Local Web Server (Recommended)
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js
npx http-server -p 8000
```
Then open `http://localhost:8000/launcher.html` in your browser.

### Option 3: Live Server
If you use VS Code, install the Live Server extension and right-click on `launcher.html` → "Open with Live Server".

## 🕹️ Game Controls

| Game | Controls |
|------|----------|
| **Tetris** | ← → Move, ↑ Rotate, ↓ Soft Drop, Space Hard Drop, P Pause |
| **Pac-Man** | ← → ↑ ↓ Move, P Pause |
| **Snake** | ← → ↑ ↓ or WASD Move, R Restart, Space Pause |
| **Pong** | ← → or W/S Move, Space Pause |
| **Breakout** | Mouse Move, ← → Move, Space/Click Launch, P Pause |
| **Space Invaders** | ← → Move, Space Fire, P Pause |
| **Asteroids** | ↑ Thrust, ← → Rotate, Space Fire, P Pause |
| **Galaxian** | ← → Move, Space Fire, P Pause |
| **Frogger** | ← → ↑ ↓ Move, P Pause |
| **Donkey Kong** | ← → Move, ↑ ↓ Climb ladders, Space Jump, P Pause |
| **Centipede** | ← → Move, ↑ ↓ Aim, Space Fire, P Pause |

## 🏆 Features

- **High Score Tracking** - Each game saves your best score locally
- **Pause Functionality** - Pause any game with P key
- **Responsive Controls** - Keyboard and mouse controls
- **Visual Effects** - Glowing elements, particle effects, smooth animations
- **Progressive Difficulty** - Games get harder as you advance
- **Back Button** - Easy navigation back to game launcher

## 🎨 Customization

Each game is self-contained in a single HTML file with embedded CSS and JavaScript. Feel free to customize:

- Colors and themes
- Game speed and difficulty
- Canvas size
- Control schemes

## 🛠️ Technical Details

- **Pure HTML5 Canvas** - No external libraries required
- **Vanilla JavaScript** - Clean, readable code
- **Self-contained** - Each game is a single HTML file
- **LocalStorage** - High scores persist between sessions
- **RequestAnimationFrame** - Smooth 60 FPS gameplay

## 📝 Credits

Created by **Grteam**
Contact: grteam2@gmail.com

## 📜 License

This project is open source and available for personal and educational use.

## 🤝 Contributing

Feel free to fork this repository, add new games, or improve existing ones!

## 🎯 Future Enhancements

- Sound effects
- Mobile touch controls
- High score leaderboard (server-side)
- Additional classic arcade games
- Multiplayer modes

---

**Enjoy the games! 🎮**
