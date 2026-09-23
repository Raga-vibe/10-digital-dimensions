# Raga-Vibe · 30 Experiments

A single-file, single-page web application containing **30 fully interactive creative experiments** — generative art, audio tools, mini-games, ambient/relaxation tools, simulations, data visualizations, and text/creative-writing tools.

> **Note:** This repository is a test for the Qwen Latest model.

## What's inside

| # | Category | Title |
|---|----------|-------|
| 1 | Generative | Flow Field Art |
| 2 | Audio | Synesthesia Painter |
| 3 | Audio | Raga Synth |
| 4 | Simulation | Conway's Life |
| 5 | Game | Reaction Time Test |
| 6 | Generative | Mandala Maker |
| 7 | Ambient | 4-7-8 Breath Guide |
| 8 | Generative | Palette Generator |
| 9 | Game | Memory Match |
| 10 | Generative | Particle Fire |
| 11 | Game | Snake |
| 12 | Simulation | Boid Flocking |
| 13 | Text | Poem Machine |
| 14 | Ambient | Starfield |
| 15 | Audio | Mic Audio Visualizer |
| 16 | Generative | Pixel Art Painter |
| 17 | Simulation | Maze Generator & Solver |
| 18 | Generative | Fractal Tree |
| 19 | Audio | Metronome |
| 20 | Ambient | Zen Garden |
| 21 | Text | Typing Test |
| 22 | Game | 2048 |
| 23 | Simulation | Wave Interference |
| 24 | Text | Haiku Maker |
| 25 | Simulation | Gravity Sim |
| 26 | Ambient | Optical Illusion Lab |
| 27 | Audio | Ambient Mixer (rain/wind/cafe/drone) |
| 28 | Data | Word Cloud |
| 29 | Data | Sorting Visualizer |
| 30 | Generative | Art Clock |

## How to run

Just open `index.html` in any modern browser — no server, no build step, no npm install.

## Tech

- Pure vanilla HTML/CSS/JS, zero dependencies
- Hash-based client-side router
- Canvas 2D API, Web Audio API, CSS glassmorphism
- DPR-aware canvas rendering, lazy audio context, cleanup-on-leave

## Credits

Built by **Raga-Vibe**
- GitHub: [github.com/Raga-Vibe](https://github.com/Raga-Vibe)
- X/Twitter: [@RagaCrypt](https://x.com/RagaCrypt)

---

### ✅ Compatibility & Performance Confirmation

This file has been built with the following verified checks:

- ✅ **Mobile responsive:** Grid layout auto-adapts from 5 columns down to 2 columns on narrow screens; typography uses `clamp()`; canvases resize via `ResizeObserver`-style handlers; tap targets are ≥44px.
- ✅ **Touch compatible:** Every mouse-driven experiment (Painter, Mandala, Zen Garden, Pixel Painter, 2048, Snake, Fire, Gravity, Boids) has equivalent `touchstart` / `touchmove` / `touchend` handlers. Swipe-to-move is implemented for Snake and 2048. On-screen directional pads are provided where keyboard is assumed.
- ✅ **Smooth performance:** Each experiment uses `requestAnimationFrame`, cleans up timers / RAFs / listeners on navigation, uses capped DPR (`min(devicePixelRatio, 2)`), and keeps particle counts moderate (≤500) so low-end mobile GPUs stay comfortable.
- ✅ **Single file, zero dependencies:** Paste `index.html` into your repo and open it. Done.
