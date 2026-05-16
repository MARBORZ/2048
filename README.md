# 2048 Game

A classic 2048 puzzle game implementation built with vanilla JavaScript. Slide numbered tiles on a grid to combine them and create a tile with the number 2048.

## 🎮 About

This is a browser-based implementation of the popular 2048 game. The objective is to slide numbered tiles on a 4×4 grid to combine them and create a tile with the number 2048. When two tiles with the same number touch, they merge into one with their sum.

## ✨ Features

- **Pure Vanilla JavaScript** — No frameworks or libraries
- **Tile Merging Logic** — Smooth tile combination mechanics
- **Grid-Based State Management** — Clean state handling and updates
- **Keyboard Controls** — Arrow keys for tile movement
- **Responsive Design** — Works on different screen sizes
- **Score Tracking** — Keep track of your current score
- **Game Over Detection** — Automatic detection when no moves are available

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3 / SCSS** — Styling with preprocessor
- **Vanilla JavaScript** — Game logic and DOM manipulation
- **ES6 Modules** — Modular code structure

## 📁 Project Structure

```
2048/
├── css/           # Compiled CSS files
├── scss/          # SCSS source files
├── js/            # JavaScript modules
├── img/           # Images and favicon
├── index.html     # Main HTML file
└── README.md      # Documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) A local web server for development

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd 2048
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js http-server
npx http-server
```

3. Navigate to `http://localhost:8000` in your browser

## 🎯 How to Play

1. Use **arrow keys** (↑ ↓ ← →) to move tiles
2. When two tiles with the same number touch, they **merge into one**
3. After every move, a new tile appears randomly
4. The goal is to create a tile with the number **2048**
5. The game ends when no more moves are possible

## 🎓 Learning Goals

This project was built to practice:

- **Game Logic Implementation** — State management and game rules
- **DOM Manipulation** — Dynamic UI updates without frameworks
- **Event Handling** — Keyboard input processing
- **Clean Code Architecture** — Separation of concerns
- **Vanilla JavaScript** — Building complex interactions without libraries

## 📝 Code Highlights

- **Modular Structure** — Game logic separated from UI rendering
- **State Management** — Clean grid state updates
- **Collision Detection** — Tile merging algorithm
- **Animation** — Smooth tile movements

## 🔧 Development

### SCSS Compilation

If you modify SCSS files, compile them to CSS:

```bash
# Using sass CLI
sass scss/style.scss css/style.css

# Watch mode
sass --watch scss:css
```

## 📄 License

This project is licensed under the terms specified in `LICENSE.txt`.

## 🙏 Acknowledgments

- Original 2048 game by Gabriele Cirulli
- Built as a learning project to understand game mechanics and vanilla JavaScript

---

**Note:** This is a portfolio project demonstrating vanilla JavaScript skills and game development fundamentals.
