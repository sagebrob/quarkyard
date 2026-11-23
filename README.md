# Quarkyard

Free interactive science simulations at https://quarkyard.com (split out of ipassedmath.com).

## Stack
- Plain HTML, no framework, no build step. Each simulator is one self-contained `index.html`.
- Hosted on Cloudflare Pages, auto-deploys on push to `main`. Build command: none. Output directory: `/` (repo root).

## Layout
- `index.html` — the hub page (was `ipassedmath.com/simulators/`); thumbnails in `thumbs/`
- `<name>-simulator/index.html` (+ `index-es.html` for Spanish where available)
- `ice-vs-cold-water/`
- `_redirects` — old `/simulators/` and lesson-numbered URLs

## Local preview
`python3 -m http.server 8080` from the repo root, then open http://localhost:8080
