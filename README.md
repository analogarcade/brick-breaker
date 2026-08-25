# Neon Breaker

A polished, single-file Brick Breaker / Arkanoid game built with native browser technologies. It uses an HTML5 Canvas for rendering, modern vanilla JavaScript for gameplay, and the Web Audio API for procedural retro synth effects.

## Play locally

Open [`index.html`](./index.html) in a modern desktop or mobile browser. No build step, package manager, server, or external assets are required.

## Controls

- **Desktop:** `A` / `D`, `←` / `→`, or mouse / trackpad movement
- **Mobile:** touch and drag horizontally across the game area
- **Launch:** click or tap the game board, or press `Space`
- **Pause / resume:** `Escape` or `Space`

## Features

- Responsive 16:9 neon synthwave canvas
- Smooth `requestAnimationFrame` game loop
- Angular paddle bounce based on impact position
- Six rows of colored bricks with row-based scoring
- Three lives, persistent best score, game-over, pause, and victory states
- Procedural Web Audio effects for paddle hits, brick breaks, victory, and game over
- Colorful brick-break particle bursts
- Wide Paddle and Multi-Ball power-ups
- Keyboard, mouse, trackpad, and touch input
- Zero external dependencies

## Project structure

```text
brick-breaker/
├── index.html   # Complete game: HTML, CSS, rendering, physics, audio, and input
└── README.md    # Project documentation
```

## Browser support

Use a current version of Chrome, Edge, Firefox, or Safari. Audio starts after a user interaction, as required by modern browser autoplay policies.

## License

This project is available for personal use and experimentation. Add a formal license before distributing it as an open-source project.
