# rudra.patel — personal portfolio

Live at **[https://rudra5417.github.io](https://rudra5417.github.io)**

Monochrome-build minimal, one JetBrains Mono typeface, one file. Whoop, Stormglass, clarify —
the side builds do the talking; the day job fills in the details.

## Ship it

Everything lives in `index.html` — open it, change it, push:

```bash
git add index.html && git commit -m "update" && git push
```

GitHub Pages redeploys automatically in about a minute. No build step, no frameworks, ~19 KB.

## Design

- Editorial mono-lab: Maestro-inspired light mode — warm paper `#f3f2ec`, ink `#313130`, larger EB Garamond type, EB Garamond serif voice, Cinzel engraved section labels, IBM Plex Mono details, hairline dividers
- Experience → builds → stack → contact; builds are side projects only (the day job stays in Experience)
- Share cards: OG/Twitter meta + generated `assets/og-card.png` (1200×630)
- Konami easter egg: `↑ ↑ ↓ ↓ ← → ← → B A`
- Respects `prefers-reduced-motion`; works offline (fonts are the only network fetch, with graceful fallbacks)

## Edit markers

Search `EDIT` in `index.html` — remaining placeholder: Wattpath repo link (no public repo yet).
