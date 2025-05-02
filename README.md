# 🎮 Catch the Diamonds!

![OpenGL](https://img.shields.io/badge/OpenGL-2D%20Game-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A 2D reflex-based game where you control a catcher bowl to grab falling diamonds before they hit the ground. Built using **Python** and **OpenGL**, and rendered completely with the **Midpoint Line Drawing Algorithm** and **GL_POINTS**.

> **Assignment 02 — 2D Game Implementation**  
> **Course:** CSE423 (Computer Graphics, 0.75 credit)  
> **Lab Instructor:** Farhan Feroz [FHZ] & Arian Nuhan [CARN]  
> **Semester:** Spring 2025

---

## 🧩 Game Description

You play as a catcher bowl at the bottom of the screen. Colored diamonds fall from the top, and your job is to **catch** them. If a diamond falls and hits the ground, it's game over. As time progresses, the diamonds fall faster, increasing the challenge!

---

## 🎮 Features

- 🟣 Diamonds rendered using **8-way Midpoint Line Drawing**
- 🎯 Catcher bowl made with **4 midpoint lines** (trapezoid shape)
- 🖱️ Mouse-controlled UI with:
  - **Restart Button** (↩️)
  - **Play/Pause Button** (▶️/⏸️)
  - **Quit Button** (❌)
- 🎨 Bright, randomly colored diamonds
- 🕹️ Responsive horizontal movement using arrow keys
- ⏱️ Speed increases over time using **delta time**
- 📏 AABB-based collision detection

---

## 🕹️ Controls

| Input         | Action                         |
|---------------|--------------------------------|
| ⬅️ / ➡️       | Move catcher left/right        |
| Mouse Click   | Interact with buttons (↩️ ⏸️ ❌) |
| Restart Btn   | Starts a new game              |
| Play/Pause Btn| Toggles falling/paused state   |
| Quit Btn      | Ends the game                  |

---

## 🧮 Technical Highlights

- Implemented **Midpoint Line Drawing Algorithm** for all shapes.
- Used **zone conversion** to support drawing lines in all 8 directions using a single method.
- Applied **Axis-Aligned Bounding Box (AABB)** collision detection.
- Used **delta timing** to ensure consistent motion across different frame rates.

---

## 🔧 Installation

### Requirements
- Python 3.x
- PyOpenGL
- PyOpenGL_accelerate


---

## 📚 Related Assignments

- 🔢 [Assignment 01: 2D Transformations & Clipping](https://github.com/MonowarHusain/CSE423/tree/main/LAB/LAB1)
- 💎 **Assignment 02: Catch the Diamonds!** (this project)
- 🎮 [Assignment 03: Bullet Frenzy 3D](https://github.com/MonowarHusain/Bullet-Frenzy)

---

## 🧑‍💻 Author

**Monowar Husain**  
📧 [monowar@monowar.me](mailto:monowar@monowar.me)  
📧 [monowarhusainomi@gmail.com](mailto:monowarhusainomi@gmail.com)  
🌐 [monowar.me](https://monowar.me)
