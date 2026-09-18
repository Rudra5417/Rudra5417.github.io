# rudra.patel — personal portfolio

Live at **[https://rudra5417.github.io](https://rudra5417.github.io)**

Single-file static site — no frameworks, no build step. Content from my resume and GitHub: live operations at Epic Games (Fortnite Discover), data science (M.S., USC), and game analytics engineering.

## Edit

Everything lives in `index.html` (search `EDIT` for the few placeholders — LinkedIn URL, Wattpath repo link). Open it, change it, push to `main`:

```bash
git add index.html && git commit -m "update" && git push
```

GitHub Pages redeploys automatically in about a minute.

## Cinematic opening

The hero is a **WebGL 3D scene** (three.js from CDN — the only external dependency): floating islands with real depth fog, a balloon bus, glider drops with physics, loot beams, a closing storm eye with lightning, embers, campfires and stars. Camera pushes in at load and follows your mouse. If three.js can't load (offline, old device), it falls back to an asset-free 2D canvas flyover, so the hero never breaks.

To use real footage instead of the 3D scene, drop a muted **`intro.mp4`** (5–15s, landscape, H.264) next to `index.html` — it auto-plays fullscreen and the 3D scene stands down. Keep it under ~10 MB.

## Colophon

- Dark, animated, single-page design — vanilla HTML / CSS / JS
- Type: Space Grotesk, Inter, JetBrains Mono (Google Fonts)
- Respects `prefers-reduced-motion` and touch devices
