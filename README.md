# Intern1Work

**Field Notes · Issue 01** — a Marketing & Operations internship reflection from a Singapore ride-hailing app, presented as a one-off digital magazine.

## Contents

- `index.html` — the complete single-page site (all CSS and JS inlined; no build step required). Open it directly in a browser, or serve it with any static file server.

## Assets

All artwork and video are embedded directly in `index.html` as inline data URIs (covers, figures, the hero mascot, and the two clips), so the site is fully self-contained and needs no `assets/` directory. The only external reference is the small `rima-cursor.png` cursor sprite, which falls back to an inline SVG when absent. Fonts are loaded from Google Fonts / Fontshare over the network.

## Viewing locally

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```
