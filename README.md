# 🎮 2048 Game

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat&logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

A browser version of the classic **2048** puzzle game, built with vanilla JavaScript — no frameworks.
Slide the tiles, merge equal numbers and try to reach the **2048** tile!

---

## 🔗 Live Preview

👉 **[Play the game](https://shtoikoihor.github.io/2048-game-in-browser/)**

---

## 🛠 Technologies Used

| Category        | Tools                                      |
| --------------- | ------------------------------------------ |
| Markup & Styles | HTML5, SCSS, CSS transitions, `@keyframes` |
| Logic           | JavaScript (ES6+, classes, modules)        |
| Build           | Parcel                                     |
| Code quality    | ESLint, Prettier, Stylelint                |
| Testing         | Jest, Cypress                              |

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- npm

### Installation

```bash
git clone https://github.com/shtoikoihor/2048-game-in-browser.git
cd 2048-game-in-browser
npm install
```

### Run locally

```bash
npm start
```

Open the URL shown in the terminal (usually `http://localhost:8080`).

### Other scripts

```bash
npm run lint   # check code style
npm test       # run tests
```

---

## ✨ Features

- 4×4 board that starts with two random tiles
- Move tiles with the arrow keys
- Equal tiles merge — each tile merges only once per move
- A new tile (2, or less often 4) appears after every valid move
- Score grows with every merge
- Win message when the **2048** tile is reached
- Game over message when no moves are left
- Start / Restart button
- Smooth animations for appearing and moving tiles

### 🎹 Controls

| Key | Action     |
| --- | ---------- |
| `←` | Move left  |
| `→` | Move right |
| `↑` | Move up    |
| `↓` | Move down  |

---

