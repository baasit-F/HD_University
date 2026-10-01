# Humble Dreams University — Website

Brand website / store concept for **Humble Dreams University** — *Dream Big. Stay Humble.*

## Structure
- `site/` — homepage prototype (static HTML/CSS/JS)
  - `index.html` — the page
  - `assets/` — product + packaging images used by the page
- `design/` — original brand references (packaging, acceptance letter, product mockups)

## Run locally
```bash
python3 -m http.server 4173 --directory site
```
Then open http://localhost:4173

## Deploy (Netlify)
Connect this repo in Netlify (Add new site → Import from Git). `netlify.toml` sets the publish directory to `site/` with no build command, so the defaults just work. The mockup sends a `noindex` header so it stays out of search results.

## Status
First design draft. Prices and logo artwork are placeholders. No testimonials until real customer content exists. Cart and admissions form are front-end only (no data is sent). Planned next step: convert to a Shopify theme for real checkout.
