# Zombie Whomper

Playable HTML5 production prototype.

## Architecture
- `index.html` — game shell and controls
- `style.css` — responsive presentation/mobile controls
- `game.js` — gameplay runtime, camera, combat, HUD, projectiles and effects
- `assets/` — clean runtime art only

## Production art rule
Concept sheets and animation atlases stored in the repository root are **reference/source art**, not runtime sprites. They must never be drawn directly into gameplay. Runtime animation will use isolated transparent frames placed under `assets/production/`.

## Controls
A/D or arrows = move · W/Space = jump · J = WHOMP · K = throw beer.
