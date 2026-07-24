# AB7C32 — Angry Birds (Stage 7: On-Screen Scoring)

A browser "Angry Birds" style slingshot game. Drag the bird back in the
slingshot and release to launch it into a tower of boxes and logs, knocking
out the pigs.

This is **Stage 7** of the Angry Birds build curriculum. Its headline feature
is **on-screen scoring**: each pig exposes a `.score()` method. When a pig is
struck hard enough it is removed from the world and fades out, and its
`score()` call increments the running score drawn on the canvas — so you earn
points for every pig you take down.

## Built with

- [p5.js](https://p5js.org/) — canvas rendering, input, and sprites
- [matter.js](https://brm.io/matter-js/) — 2D physics (gravity, collisions, constraints)

## How to run

- **Simplest:** open `index.html` directly in a web browser.
- **Via a static server** (recommended, avoids image-loading quirks):
  ```
  python3 -m http.server 8000
  ```
  then visit <http://localhost:8000>.
- **GitHub Pages:** enable Pages for this repo and open the published URL.

## Controls

- **Mouse drag** — pull the bird back in the slingshot.
- **Release the mouse** — launch the bird toward the tower.
- Watch the **score** update on screen as pigs are knocked out.
