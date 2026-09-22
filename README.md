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

- Mono-lab minimal: near-black `#0b0b0c`, hairline dividers, numbered work rows, one cyan accent
- Experience → builds → stack → contact; builds are side projects only (the day job stays in Experience)
- Share cards: OG/Twitter meta + generated `assets/og-card.png` (1200×630)
- Konami easter egg: `↑ ↑ ↓ ↓ ← → ← → B A`
- Respects `prefers-reduced-motion`; works offline (fonts are the only network fetch, with graceful fallbacks)

## Edit markers

Search `EDIT` in `index.html` — remaining placeholder: Wattpath repo link (no public repo yet).
