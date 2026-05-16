<div align="center">

# 3D Snake Game

**Three.js · JavaScript · HTML5 · WebGL · 3D Graphics**

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Three.js](https://img.shields.io/badge/Three.js-3D-black?style=flat-square&logo=three.js&logoColor=white)](https://threejs.org)
[![HTML5](https://img.shields.io/badge/HTML5-Web-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![WebGL](https://img.shields.io/badge/WebGL-Renderer-990000?style=flat-square)]()

</div>

---

## Overview

A **browser-based 3D Snake game** built with **Three.js**, HTML, and JavaScript. The classic Snake gameplay is reimagined in a 3D WebGL environment — the snake grows as it eats food, and the game ends if the head collides with the body or the boundary walls.

No frameworks, no dependencies beyond Three.js — runs directly in the browser.

---

## Gameplay

- The snake moves continuously across a 3D grid
- Eating food increases the snake's length
- Food spawns at a random position within the grid after each eat
- **Game over** if the snake's head touches:
  - Its own body
  - The edge of the arena

---

## Project Structure

```
snakeGame/
│
├── SnakeGame.html     # Entry point — loads Three.js and game script
└── SnakeGame.js       # Full game logic — snake, food, grid, movement, collision
```

---

## How to Play

1. Open `SnakeGame.html` in any modern browser
2. Use **arrow keys** to control the snake's direction
3. Eat the food to grow longer
4. Avoid hitting the walls or yourself

No installation or build step required.

---

## Technical Highlights

| Feature | Detail |
|---|---|
| **3D rendering** | Three.js WebGL renderer with perspective camera |
| **Grid system** | 10×10 grid mapped to 3D coordinate space |
| **Snake movement** | Timer-driven forward movement at 250ms intervals |
| **Food placement** | Random grid position, collision-checked against snake body |
| **Collision detection** | Head vs. body and head vs. boundary checks each tick |
| **3D scene** | GridHelper for floor · BoxGeometry for snake & food segments |

---

## Tech Stack

| Component | Technology |
|---|---|
| 3D Engine | Three.js |
| Language | JavaScript (ES6) |
| Markup | HTML5 |
| Renderer | WebGL |

---

## Author

<div align="center">

**Mainuddin Monsur Robin**
*M.Sc. Information and Communication Engineering — HAW Hamburg*

[![GitHub](https://img.shields.io/badge/GitHub-MM--Robin-181717?style=flat-square&logo=github)](https://github.com/MM-Robin)

</div>
