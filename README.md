# splits-site

Marketing site for Splits, live at https://joinsplits.app. Plain HTML/CSS, hosted on GitHub Pages from `main`.

- `index.html`: home
- `privacy/`, `terms/`, `support/`: one `index.html` each, giving clean URLs like `/privacy`
- `assets/style.css`: shared styles (brand colours live at the top)
- `assets/logo.svg`: podium-pulse mark, also used as the favicon
- `CNAME`: tells GitHub Pages to serve the site at joinsplits.app

Preview locally: `python3 -m http.server`, then open http://localhost:8000.
