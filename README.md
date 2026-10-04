# rudra.patel — personal portfolio

Live at **[https://rudra5417.github.io](https://rudra5417.github.io)**

Light editorial, one file: EB Garamond voice, Cinzel engraved labels, IBM Plex Mono details.
Five builds lead — Nightjar, whoop5-protocol, AIRWAVE, rmem, Stormglass — the day job stays in Experience.

## Ship it

Everything lives in `index.html` — open it, change it, push:

```bash
git add index.html && git commit -m "update" && git push
```

GitHub Pages redeploys automatically in about a minute. No build step, no frameworks, ~22 KB.

## Design

- Maestro-inspired light mode — warm paper `#f3f2ec`, deep ink `#1a1a18`, larger serif type; Cinzel section labels, IBM Plex Mono details, hairline dividers
- Experience → builds → contact; builds are side projects only (the day job stays in Experience), and skills live in the résumé rather than the page
- Share cards: OG/Twitter meta + generated `assets/og-card.png` (1200×630)
- Konami easter egg: `↑ ↑ ↓ ↓ ← → ← → B A`
- Respects `prefers-reduced-motion`; works offline (fonts are the only network fetch, with graceful fallbacks)

## Edit markers

Search `EDIT` in `index.html` — remaining placeholder: Wattpath repo link (no public repo yet).
