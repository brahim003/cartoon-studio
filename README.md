# cartoon-studio

Brahim's cartoon-shorts project: reusable characters + 3D environments.

- `rig/`: character-skill-build (MIT), SVG + GSAP characters (vet, boy, girl, barista, granny, manager, dog, cat). Use `rig/character.slim.js` + `rig/vendor/gsap-3.15.1.min.js`.
- `assets/kenney/`: Kenney CC0 3D kits as .glb (castle, retro-fantasy, pirate, mini-forest, nature, survival, food, factory). List: `assets/catalog.json`.
- `env/test.html`: three.js test scene (sunset light, GLB models), screenshot with `env/shot.mjs` (Playwright).

Rules (cartoon style): sky, clouds, sunset and ground are drawn in code (no photo HDRI); captions word-exact (max 3 words); rich environments; golden hour; cinematic camera moves; characters that turn head/body.
Licenses: Kenney CC0, character-skill-build MIT.
