# rudra.patel — personal portfolio

Live at **[https://rudra5417.github.io](https://rudra5417.github.io)**

Single-file static site — no frameworks, no build step. Content from my resume and GitHub: live operations at Epic Games (Fortnite Discover), data science (M.S., USC), and game analytics engineering.

## Edit

Everything lives in `index.html` (search `EDIT` for the few placeholders — LinkedIn URL, Wattpath repo link). Open it, change it, push to `main`:

```bash
git add index.html && git commit -m "update" && git push
```

GitHub Pages redeploys automatically in about a minute.

## Cosmos background

The site sits on a realistic starfield — a baked 512px cosmos tile repeats across the whole page (fixed, so it stays put while you scroll), and the hero adds ~110 bright stars that gently twinkle. No frameworks, no CDN, no animation dependencies — one file, works offline.

## Colophon

- Dark, animated, single-page design — vanilla HTML / CSS / JS
- Type: Space Grotesk, Inter, JetBrains Mono (Google Fonts)
- Respects `prefers-reduced-motion` and touch devices
