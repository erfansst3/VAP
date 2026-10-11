# DUST OPS — Browser FPS

A zero-build, browser-playable 3D FPS prototype using Three.js. The arena is built from procedural geometry, with a Dust2-inspired layout, first-person weapon viewmodels, weapon switching, recoil, scoped AWP, hit detection, headshots, respawning bots, minimap, HUD and touch controls.

## Run locally

Open `index.html` through a local web server (ES modules require HTTP), for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Controls

- Desktop: WASD move, mouse aim, left click fire, right click scope, Shift walk, Ctrl crouch, Space jump, R reload, 1–5 switch weapons, Q cycle, Esc pause.
- Touch: left stick move, drag the scene to aim, FIRE, RELOAD, JUMP and SWAP controls.

## Deployment

The included GitHub Actions workflow publishes the static site to GitHub Pages after the Pages source is set to **GitHub Actions** in repository Settings → Pages.

## Assets and scope

The source and 3D geometry in this repository are original/procedural. This prototype does not include proprietary Counter-Strike map files, character models, weapon models, sounds or textures, so it is a playable foundation rather than a 1:1 recreation. Three.js is loaded from jsDelivr at runtime.
