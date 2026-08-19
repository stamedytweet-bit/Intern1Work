# Intern1Work

**Field Notes · Issue 01** — a Marketing & Operations internship reflection from a Singapore ride-hailing app, presented as a one-off digital magazine.

## Contents

- `index.html` — the complete single-page site (all CSS and JS inlined; no build step required). Open it directly in a browser, or serve it with any static file server.

## Assets

The page references local media under an `assets/` directory that is not yet in the repo. Every image and video has a built-in placeholder fallback, so the site renders fully without them. To add the real media, create the following files:

```
assets/
├── rima-hero.png          # cover mascot illustration
├── rima-cursor.png        # cursor companion sprite
├── art-01-cover.jpg … art-08-cover.jpg
├── art-01-fig-01.jpg … art-08-fig-02.jpg
└── video/
    └── art-09-closing.mp4
```

## Viewing locally

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```
