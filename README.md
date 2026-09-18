# Eaze Landing Site

Official landing site for [Eaze](https://github.com/MR-STARK87/Eaze) — the human-centric programming language.

Live at **https://mr-stark87.github.io/Eaze-Landing-Site/** (GitHub Pages, `main` branch, site root).

## Pages

| File | Route | Content |
| --- | --- | --- |
| `index.html` | `/` | Hero, use cases, philosophy ("Less friction. More understanding."), features, live Eaze snippet, roadmap, CTA |
| `behind.html` | `/behind.html` | Creator narrative: the question, the vision ("Programming for humans first"), the philosophy ("Learning before complexity") |
| `download.html` | `/download.html` | Windows installer + portable builds (v1.0.0, via GitHub releases), system requirements, run-from-source |
| `404.html` | 404 | Fallback route for Pages |
| `style.css` | — | Shared theme: light/dark tokens, responsive nav, reduced-motion support |
| `favicon.svg` | — | Site icon |

## Local preview

Any static server works, e.g. `npx serve .` or `python -m http.server`, then open http://localhost:3000 (or :8000).

## Deploy

Push to `origin/main` — Pages rebuilds automatically (legacy branch deploy). Verify with `gh api repos/MR-STARK87/Eaze-Landing-Site/pages`.
