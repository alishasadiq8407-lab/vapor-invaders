# 👾 VAPOR INVADERS
### RETRO-FUTURISTIC COMBAT SYSTEM V1.0

> A neon-drenched, vaporwave-styled Space Invaders game built for the browser. Destroy waves of pixel enemies, rack up your high score, and vibe to synthwave music — all in one sleek retro-futuristic interface.

🔗 **Live Demo:** [vaporinvaders-120980617997.us-west1.run.app](https://vaporinvaders-120980617997.us-west1.run.app/)

---

## 🎮 Gameplay

Battle through waves of descending pixel invaders across multiple threat levels. Each wave gets faster and more aggressive. Survive as long as you can and top the high score board.

- **Sector:** NEON-84
- **Status:** ACTIVE
- **Threat Level:** Increases each wave

---

## ✨ Features

- 👾 **5 rows of enemies** in 3 distinct color tiers — pink, purple, green, and yellow
- 🏆 **High Score tracker** — displayed in the top-right corner at all times
- 📋 **Mission Log panel** — live status showing threat level, sector, and game state
- 🎵 **Built-in Music Player** — plays synthwave tracks (e.g. *Neon Nights* by Synthwave Pro) with prev/play/next controls
- 🌌 **Dark vaporwave aesthetic** — deep purple background, neon grid, glowing UI panels
- 🕹️ **Keyboard controls** — Arrow keys / WASD to move, Space to fire
- 📺 **Retro monospace UI** — pixel-perfect fonts and color-coded HUD elements

---

## 🕹️ Controls

| Key | Action |
|-----|--------|
| `← →` or `A D` | Move player left / right |
| `Space` | Fire bullet |

---

## 🖥️ UI Layout

```
┌─────────────────────────────────────────────────────────┐
│  [VAPOR INVADERS logo]              [HIGH SCORE: 00300]  │
├──────────────────┬──────────────────────────────────────┤
│  MISSION LOG     │         GAME CANVAS                  │
│  Status: ACTIVE  │   SCORE: 00020                       │
│  Threat Level: 1 │   [ enemy grid — 5 rows x 10 cols ]  │
│  Sector: NEON-84 │                                      │
│                  │         [ player ship ]              │
│  CONTROLS        │                                      │
│  ARROWS / WASD   │                                      │
│  SPACE           │                                      │
├──────────────────┴──────────────────────────────────────┤
│  🎵 Neon Nights — Synthwave Pro        [⏮  ▶  ⏭]       │
└─────────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

- **HTML5 / CSS3 / JavaScript** — no frameworks, no build tools
- **HTML5 Canvas** — real-time game rendering
- **Web Audio API** — procedural retro sound effects
- **CSS custom properties** — consistent neon vaporwave theming
- **Google Cloud Run** — serverless deployment

---

## 🚀 Run Locally

No installation needed. Just clone and open:

```bash
git clone https://github.com/YOUR_USERNAME/vapor-invaders.git
cd vapor-invaders
open index.html   # or double-click it in your file explorer
```

---

## ☁️ Deploy

Since it's a single HTML file, deploy anywhere in seconds:

| Platform | How |
|----------|-----|
| **GitHub Pages** | Push repo → Settings → Pages → main branch |
| **Netlify** | Drag & drop `index.html` at netlify.com/drop |
| **Google Cloud Run** | Wrap in nginx Docker container |

---

## 📁 Project Structure

```
vapor-invaders/
├── index.html       # Full game — HTML + CSS + JS in one file
└── README.md        # This file
```

---

## 📜 License

MIT — free to play, remix, and deploy.

---

*© 1984 VAPOR-CORP // ALL RIGHTS RESERVED // EST. IN THE FUTURE*
