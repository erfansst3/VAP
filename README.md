# Dust II — Browser FPS

A desktop-first, first-person browser FPS that loads the uploaded `de_dust2.obj`, `de_dust2.mtl` and the matching TGA textures instead of the earlier placeholder arena. The map is converted from its Z-up OBJ coordinate system at runtime. AK-47, AWP and knife first-person models are GLB assets in `public/models/`; animated soldier opponents use the credited open-source model project listed in `THIRD_PARTY_NOTICES.md`.

## Play

Serve this directory over HTTP (ES modules and texture loading do not work from `file://`):

```bash
python -m http.server 8000
```

Open `http://localhost:8000`. GitHub Pages deployment is configured by `.github/workflows/pages.yml`; in repository Settings → Pages, choose **GitHub Actions** as the source if it is not already enabled.

## Controls

- `WASD`: move; mouse: look; left click: fire; right click: AWP scope.
- `Shift`: walk; `Ctrl`: crouch; `Space`: jump; `R`: reload; `1` AK-47, `2` AWP, `3` knife; `Q` cycles weapons; `Esc` pauses.
- Touch controls are included as a basic fallback, but desktop mouse and keyboard are recommended.

## Current scope

This is a single-player prototype: the original map model and textures, imported weapon viewmodels, animated opponent models, hitboxes, shooting, recoil, minimap and a basic bot combat loop. It is not yet a 1:1 recreation of Counter-Strike’s movement, weapon handling, multiplayer, full animations or AI. Original CS game assets are not bundled. Review `THIRD_PARTY_NOTICES.md` for model attribution and the source/rights note for the uploaded map files.
