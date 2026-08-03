# raoket.github.io

Personal site for Abhishek Rao, Solutions Architect.

A single self-contained `index.html`: inline CSS and JS, no framework, no build step,
no dependencies. Light and dark themes with a manual toggle, persisted in
`localStorage`. Served by GitHub Pages from `main`.

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire site |
| `Abhishek-Rao-Resume.pdf` | Résumé, linked from the hero and footer |
| `.nojekyll` | Skip Jekyll processing |

## Local preview

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Push to `main`. Pages serves from the repository root.

## Adding a custom domain later

Add a `CNAME` file containing the bare domain, then point DNS at GitHub Pages.
No other change is needed.
