# TIMEPASS-SNAKE-GAME

A classic Snake game implemented with HTML5 Canvas and JavaScript, featuring smooth animation using `requestAnimationFrame`.

## 🎮 Features

- Smooth snake movement using `requestAnimationFrame`
- Consistent game speed (5 cells per second)
- Classic Snake gameplay with growing mechanics
- Score tracking and high score persistence
- Responsive design that works on desktop and mobile
- Keyboard controls (Arrow Keys / WASD)
- Touch/click support for restarting
- Visual feedback with grid lines and color gradient snake
- Game over overlay with restart instructions

## 🕹️ How to Play

1. Open `snake.html` in any modern web browser
2. Press **Space** or click/tap to start the game
3. Use **Arrow Keys** or **WASD** to move the snake
4. Eat the red food to grow and increase your score
5. Avoid hitting the walls or yourself
6. Press **Space** or click/tap to restart after game over

## 🛠️ Technical Implementation

This implementation features:

- **requestAnimationFrame Game Loop**: Instead of fixed intervals, uses browser's refresh rate for smooth animation
- **Time-based Movement**: Maintains consistent speed regardless of actual frame rate
- **Canvas Rendering**: Efficient 2D drawing with grid lines and visual enhancements
- **State Management**: Clean separation of game logic (init, update, draw, gameOver)
- **Input Handling**: Robust keyboard and touch event handling

### Key Variables
- `CELL = 20`: Size of each grid cell in pixels
- `SNAKE_SPEED = 5`: Movement speed in cells per second
- `COLS` & `ROWS`: Calculated based on canvas size and cell size

## 📁 Files

- `snake.html`: Complete game implementation (HTML, CSS, JavaScript)
- `README.md`: This file

## 🚀 Running the Game

Simply open `snake.html` in your browser:
```bash
# Or double-click the file in your file explorer
open snake.html  # macOS
start snake.html # Windows
xdg-open snake.html # Linux
```

## 🔧 Development

To modify the game:
1. Edit `snake.html` - all code is self-contained in this single file
2. Adjust constants at the top of the script section:
   - `SNAKE_SPEED`: Change game difficulty
   - `CELL`: Adjust grid size (affects overall canvas scaling)
   - Colors and styling in the CSS section

## 🎯 Future Enhancements

Potential improvements:
- Add sound effects
- Implement different difficulty levels
- Add pause functionality
- Store high scores in localStorage
- Add mobile-specific touch controls for direction
- Create separate CSS and JS files for better organization


*Enjoy playing Snake! Relive the classic arcade experience with modern web technologies.*
