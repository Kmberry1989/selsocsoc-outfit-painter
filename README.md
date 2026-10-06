# Outfit Painter — Selfie Social Society

Paint outfits directly on the actual in-game 3D avatar with the real texture
wrapped on it. Part of the Creator Suite (four external editors for expanding
the game).

## Run it
Open `index.html` in a browser — fully self-contained.

## Pipeline
1. Paint the outfit on the 3D avatar
2. Export the 1024×1024 PNG
3. Drop it in the game repo's `assets/outfit-textures/` + register in `manifest.json`
4. Push — Vercel auto-deploys

## Rules
- Everyday casuals: monochrome (tint-ready), no `unlock` field (free)
- Seasonal/event outfits: `unlock: {type:"festival", season:...}` in the manifest
- Peg-shaped bodies: paint sleeves/pant legs as texture — never geometry

Game repo: `Kmberry1989/selsocsoc`
