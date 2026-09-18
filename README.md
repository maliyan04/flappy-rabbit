# Flappy Rabbit 🐰

A lightweight, responsive browser game — **hop, dodge, and score** as you guide a brave little rabbit through endless carrot obstacles.

**▶️ Play now:** [https://maliyan04.github.io/flappy-rabbit/](https://maliyan04.github.io/flappy-rabbit/)

---

## 📖 About

**Flappy Rabbit** is a fast, casual arcade game inspired by the classic Flappy Bird formula. You control a rabbit that must fly through gaps between carrot-shaped pipes. One tap = one flap. Time your flaps carefully, avoid the carrots, and rack up the highest score you can.

> **Hop · Dodge · Score**

---

## ✨ Features

- 🐇 **Addictive one-tap gameplay** — simple to learn, hard to master
- 🥕 **Carrot-themed obstacles** — pipes reimagined as giant carrots with leafy tops
- 📱 **Fully responsive** — auto-scaling canvas that fits phones, tablets, laptops & desktops
- 🏆 **Best score saving** — your highest score is stored locally via `localStorage`
- 🎨 **Hand-drawn cartoon aesthetic** — Chewy font, warm sunset palette, animated clouds & particles
- 🔊 **Lightweight sound effects** — synthesized via Web Audio API (zero audio files)
- ✨ **Juicy feedback** — screen shake, score pop animation, and particle bursts on impact
- ⚡ **Zero dependencies** — pure HTML, CSS & JavaScript, no frameworks
- 📴 **Offline-ready** — works entirely in the browser, no server required

---

## 🎯 How to Play

1. **Tap** the screen (or press **Space**) to make the rabbit flap upward.
2. **Release** — the rabbit falls due to gravity.
3. **Guide** the rabbit through the gap between the carrot pipes.
4. **Score** a point each time you pass a pipe.
5. **Don't crash** — hitting a pipe or the ground ends the run.

### Goal
Survive as long as possible and beat your **best score**.

---

## 🕹️ Controls

| Platform | Action |
|---|---|
| **Desktop** | `Space` or `↑` (Up Arrow) to flap · Mouse click |
| **Mobile / Tablet** | Tap anywhere on the screen to flap |
| **All** | Click the **About** button (top-right) for developer info |

---

## 🖥️ Tech Stack

- **HTML5 Canvas** — smooth 60 FPS rendering
- **CSS3** — responsive wrapper, `clamp()`, container queries, safe-area support
- **Vanilla JavaScript (ES6)** — no frameworks, no build step
- **Web Audio API** — synthesized SFX (flap, score, hit)
- **localStorage** — best score persistence (with safe try/catch fallback)
- **Google Fonts (Chewy)** — friendly, hand-drawn typography

---

## 📂 Project Structure
