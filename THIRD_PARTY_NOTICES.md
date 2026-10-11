# Third-party assets

`public/models/ak47.glb`, `public/models/awp.glb`, and `public/models/knife.glb` are copied from [StarKnightt/counter-strike-in-browser](https://github.com/StarKnightt/counter-strike-in-browser). The animated opponent models are loaded from that project at runtime. Its project license is included below. These are independently modeled assets; they are not Valve/Counter-Strike game files.

The Dust II level and its textures (`de_dust2.obj`, `de_dust2.mtl`, `de_dust2_material_*.tga`) were supplied for this repository by the repository owner. Confirm the source and redistribution rights for those files before making the repository public or redistributing them.

## Included project license

MIT License

Copyright (c) 2026 StarKnightt

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

Third-party assets included in this repository are not covered by the MIT
license above and remain under their own terms:

- Textures baked into public/models/dust2_a.webp.glb: Poly Haven, CC0
  (asset list in tools/fetch_textures.py).
- Sound recordings in assets_src/audio_raw and their sliced versions in
  public/audio: Freesound contributors, CC0 (per-file attribution in
  public/audio/CREDITS.txt).
- assets_src/characters/Soldier.glb: the three.js example "Soldier" character
  (Mixamo rig and clips), used only as the skeleton/animation source for the
  bot build script; see the three.js repository for its terms.
- public/fonts/barlowsc-*.woff2: Barlow Semi Condensed, SIL Open Font License.

No Valve / Counter-Strike assets are included. This is a fan project and is
not affiliated with or endorsed by Valve Corporation.

