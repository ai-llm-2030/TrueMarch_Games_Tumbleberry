# Tumbleberry

**Four worlds, 16 levels, a castle boss at the end of each. Bop the blocks, grab the Muffin, find all three big coins.**

<p align="center">
  <img src="assets/screenshot-title.png" alt="Tumbleberry — title screen" width="820">
</p>

<p align="center">
  <a href="https://ai-llm-2030.github.io/TrueMarch_Games_Tumbleberry/"><b>▶ Play Tumbleberry in your browser</b></a>
</p>

## Gameplay

<p align="center">
  <img src="assets/screenshot-play.png" alt="Tumbleberry — gameplay" width="820">
</p>

## More screenshots

<table>
<tr><td width="50%"><img src="assets/screenshot-map.png" alt="The world map"><br><sub>The world map</sub></td><td width="50%"><img src="assets/screenshot-pantry.png" alt="Pip's Pantry: outfits and upgrades"><br><sub>Pip's Pantry: outfits and upgrades</sub></td></tr>
<tr><td width="50%"><img src="assets/screenshot-result.png" alt="Out of lives"><br><sub>Out of lives</sub></td><td width="50%"><img src="assets/screenshot-how.png" alt="How to play"><br><sub>How to play</sub></td></tr>
</table>

## Controls

| Keys | Action |
|---|---|
| ← → / A D | Move |
| Space / ↑ / Z | Jump (hold for higher) |
| Shift / X | Run & throw |
| ↓ | Enter a pipe |
| Esc | Menu |

## Run it yourself

No install, no build step, no server code, no network. The game runs entirely in your browser and keeps your progress in the browser's local storage.

```bash
git clone https://github.com/ai-llm-2030/TrueMarch_Games_Tumbleberry.git
cd TrueMarch_Games_Tumbleberry
python3 -m http.server 8000
# open http://localhost:8000
```

Opening `index.html` directly works too in most browsers; a local server is the most reliable way.

## What's inside

```
TrueMarch_Games_Tumbleberry/
├── index.html        the whole game: one file, plain JavaScript and <canvas>
├── lib/
│   ├── arcade.js     shared helpers: crisp canvas, frame loop, input, theme
│   └── arcade.css    shared look
├── assets/           the pictures in this README
├── LICENSE
└── README.md
```

Written from scratch in vanilla JavaScript: every sprite, background and sound is drawn or synthesised in code (Canvas 2D and the Web Audio API). No libraries, no frameworks, no third-party assets.

## About

**Tumbleberry** is one of the 120+ games made by **[TrueMarch](https://truemarch.com)**. This repository is the standalone single-player edition of the game.

## License

© 2026 TrueMarch. All rights reserved. The source is published so you can read it, learn from it and play the game; see [LICENSE](LICENSE).
