# Game 2048

> A lightweight, fully responsive clone of the classic 2048 puzzle game — play it right in your browser, no installation required.

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-Game-E34F26?logo=html5" />
  <img src="https://img.shields.io/badge/CSS3-Styling-1572B6?logo=css3" />
  <img src="https://img.shields.io/badge/JavaScript-Logic-F7DF1E?logo=javascript" />
  <img src="https://img.shields.io/badge/Responsive-Mobile%20Ready-FF69B4?logo=csswizardry" />
</p>

---

## Features

| Feature | Description |
|---------|-------------|
| 🎮 **Classic 2048 Gameplay** | Slide and merge tiles to reach the legendary 2048 tile. |
| ⌨️ **Keyboard Controls** | Use Arrow Keys or WASD to move tiles smoothly. |
| 📱 **Touch & Swipe** | Full swipe gesture support on mobile and tablet devices. |
| 🕹️ **On-Screen D-Pad** | Dedicated touch buttons for mobile users without swipe. |
| ↩️ **Undo Move** | One-step undo with a button or Ctrl+Z / Cmd+Z shortcut. |
| 🏆 **Score Tracking** | Live score counter with persistent Best Score via localStorage. |
| ✨ **Smooth Animations** | Pop-in and merge animations for an engaging visual experience. |
| 🎨 **Color-Coded Tiles** | Distinct colors for every tile value, including super tiles beyond 2048. |
| 🎯 **Win / Game Over** | Overlay messages when you hit 2048 or run out of moves. |
| 📱 **Fully Responsive** | Optimized layout for desktop, tablet, and mobile screens. |

---

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or build tools required — runs entirely client-side

---

## Usage

### 1️⃣ Open the Game
Simply open `index.html` in your browser — no installation needed.

### 2️⃣ Start Playing
- **Desktop:** Use Arrow Keys or WASD to slide tiles
- **Mobile:** Swipe on the game board or use the on-screen directional buttons
- **Undo:** Press the **Undo** button or hit Ctrl+Z to revert your last move

### 3️⃣ Merge Tiles
When two tiles with the same number touch, they merge into one! Keep merging until you reach **2048**.

### 4️⃣ Beat Your Best
Your highest score is saved automatically in the browser. Try to top it in every session!

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| **Markup** | HTML5 |
| **Styling** | CSS3 (Flexbox, Grid, CSS Animations, Media Queries) |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Storage** | localStorage (Best Score persistence) |
| **Design** | Custom responsive UI with no external CSS frameworks |

---

## Project Structure

```
game_2048/
└── index.html
```

---

## Highlights

- **Zero Dependencies** — Pure HTML, CSS, and JavaScript with no external libraries.
- **Single File** — The entire game fits in one self-contained HTML file.
- **Instant Load** — No build step, no bundler, no waiting — open and play.
- **Smart Input Handling** — Supports keyboard, mouse drag, touch swipe, and on-screen buttons.
- **Animation Polish** — Smooth tile spawn and merge animations for a premium feel.
- **Persistent Records** — Best score survives browser restarts via localStorage.
- **Super Tiles** — Game continues past 2048 with styled support for even higher values.
- **Privacy First** — All data stays locally; nothing is sent to any server.

---

## Controls

| Input | Action |
|-------|--------|
| Arrow Keys / WASD | Move tiles |
| Swipe (Touch) | Move tiles |
| On-Screen Buttons | Move tiles (mobile) |
| Ctrl+Z / Cmd+Z | Undo last move |
| New Game Button | Restart the board |

---

## Author

Built by **[Tim](https://github.com/timignatenko)**  

---

<p align="center"><b>⭐ Star this repo if you enjoyed the game!</b></p>
