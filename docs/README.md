# Trax Analytics — A Defensible Roadmap

A reveal.js presentation that condenses the Trax Analytics reset into a
roadmap argument: short term (now → June 2027), medium term (2027–2028),
long term (2028+). 19 slides, ~12 minute walkthrough, editorial light
theme.

## View it

- **Online (after GitHub Pages is enabled):** `https://<org>.github.io/<repo>/`
- **Locally:** open `index.html` directly in a browser, or run
  `python3 -m http.server 8000` in this folder and visit
  `http://localhost:8000/`.

## Speaker view

Press `S` in the browser to open the speaker view. Every slide has
speaker notes that carry the argument the slide is making.

## Enable GitHub Pages

1. Push the branch (or merge to `main`).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose
   **Deploy from a branch**.
4. Pick the branch and `/docs` as the folder. Save.
5. After ~30s, the URL appears on the Pages settings screen.

The `.nojekyll` file disables Jekyll processing so the assets are served
verbatim.

## Files

- `index.html` — the deck (reveal.js loaded from CDN; no build step)
- `styles.css` — editorial theme (FT-salmon paper, ink, oxblood, petrol)
- `.nojekyll` — opts out of Jekyll on GitHub Pages
