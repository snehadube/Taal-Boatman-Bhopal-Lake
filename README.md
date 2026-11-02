# Taal Boatman: Bhopal Lake

A 2D arcade game made with HTML, CSS and JavaScript (Canvas). Steer the boat on Badi Jheel (Bhopal), collect lotus flowers and avoid plastic waste.

**Play online:** https://YOUR-USERNAME.github.io/taal-boatman/

## Rules
- Pink lotus: +10 points. Golden lotus: +30 points and time slows for 5 seconds.
- Plastic bottle or bag: -1 life and -10 score. You have 3 lives.
- 3 lotus in a row gives a combo multiplier (x2 up to x5). Missing a lotus resets the combo.
- Every 100 points is a new level: objects fall faster and spawn more often.

## Controls
Arrow keys / A-D / mouse / touch to move. Enter or click to start, P to pause, R to restart.

## Customization
Combo multiplier scoring, golden-lotus slow-time power-up, lives-based hazard penalty, level-based difficulty, Bhopal lake theme.

## Multimedia
Self-drawn canvas sprites, pseudo-3D depth (perspective scaling, shadows, tilting boat, perspective waves), particle effects, animated clouds and ripples, sound effects generated with the Web Audio API.

## Collision detection
AABB (rectangle vs rectangle): objects collide when their edges overlap on both the X and Y axes. See `const hit = ...` in `index.html`.

## Run locally
Double-click `index.html` in Chrome or Edge.
