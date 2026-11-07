# Backyard Stripes

A photoreal-ish lawn mowing simulator for the browser, built with Three.js r170 in a single self-contained file: [`index.html`](index.html).

Open `index.html` in a modern desktop or mobile browser. It needs internet access for the Three.js module from the jsDelivr CDN; everything else (textures, grass, audio) is generated procedurally.

## Modes

- **Job**: mow the yard to 95% coverage for the customer. The customer inspects the lawn and gives a 1–5 star rating and a payout, out of a 100-point scorecard (coverage, stripe quality, cut quality, time versus a 2:30 par, and damage-free).
- **Zen**: endless free mowing with no timer or rating. Grass regrows fully in about four minutes.

## Controls

| Action | Keyboard | Touch |
|---|---|---|
| Drive / reverse | W / S or ↑ / ↓ | Left joystick (up / down) |
| Turn | A / D or ← / → | Left joystick (left / right) |
| Boost | Shift | Boost button |
| Deck up / down | Space | Deck button |
| Refuel (gas can) or sharpen (workbench) | E (press within 1.5 m) | Action button |
| Cycle camera | C | Camera button |
| Orbit chase camera | Mouse drag | Drag the right half of the screen |
| Pause | Esc | |

## Quality

Graphics presets (Low, Medium, High, Ultra) are in Settings. High is the default on desktop and Medium on touch devices. If frames stay slow during play, the game drops one preset automatically.
