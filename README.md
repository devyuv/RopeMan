# RopeMan

A fully playable, mobile-first 2D retro action-platformer — an original superhero game built with vanilla HTML5 Canvas and JavaScript (no external assets, frameworks, or libraries required).

"The city needs a hero."

## Play

Open `index.html` in any modern browser, or publish it with GitHub Pages (see below) to play at a public URL.

- **Move:** Arrow keys / A-D, or the on-screen left/right buttons on mobile
- **Jump:** Space, or the JUMP button
- **Attack:** J, or the HIT button
- **Rope:** K, or the ROPE button — fires an energy rope at the nearest glowing anchor to swing, pull, and traverse
- **Pause:** P, or the II button

## Features

- 20 hand-designed level layouts across 10 distinct environments (city streets, rooftops, industrial district, subway, harbor, sewer, laboratory, prison, carnival, enemy fortress), each with its own palette, hazards, and enemy mix
- Two multi-phase boss fights (Level 10: The Iron Beast, Level 20: The Overlord)
- 8 original enemy types with unique sprites, movement, and attack behavior
- Rope-swing pendulum physics as a core traversal and combat mechanic
- Rescue-objective and timed-rescue level types
- Mobile touch controls + full keyboard support, with layout that adapts to landscape phone screens
- Original synthesized chiptune music and sound effects via the Web Audio API (no audio files)
- CRT scanline/vignette visual filter, screen shake, and other retro presentation touches
- Level select, settings (music/SFX/CRT/shake/touch toggles), pause/resume, save progression via `localStorage`

## Deploying to GitHub Pages

1. Create a new repository on GitHub and push these files to the `main` branch (see commands below).
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, choose the `main` branch and `/ (root)` folder, then **Save**.
4. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

```bash
git init
git add .
git commit -m "Add RopeMan game"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Project structure

```
.
├── index.html    # the entire game — markup, styles, and game logic in one file
├── README.md
└── LICENSE
```

## Notes

Everything here — the character, enemies, bosses, art, music, and code — is original and was built from scratch for this project; no third-party or copyrighted assets are used.
