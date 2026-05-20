# Trax Analytics — Reset Presentation

A reveal.js deck arguing for a sequenced, three-track approach to the Trax Analytics / Data Lake initiative: protect the Logi 06/27 deadline, run platform discovery in parallel, and treat AI/ML as a separate discovery track.

## View locally

```bash
# from the repo root
python3 -m http.server 8000 --directory docs
# then open http://localhost:8000
```

Or just open `docs/index.html` directly in a browser.

## Publish via GitHub Pages

1. Push the branch to GitHub.
2. Repository **Settings** → **Pages**.
3. Under **Build and deployment**:
   - **Source:** *Deploy from a branch*
   - **Branch:** `claude/datalake-presentation-slides-ePCe4` (or whichever branch holds this commit)
   - **Folder:** `/docs`
4. Save. The deck will be served at `https://<owner>.github.io/<repo>/`.

The `.nojekyll` file in this folder tells Pages to serve the HTML as-is rather than run it through Jekyll.

## Reveal.js controls

- `→ / Space` next slide, `←` previous
- `S` opens speaker notes (visible per slide via `<aside class="notes">`)
- `F` toggles fullscreen
- `Esc` or `O` opens the slide overview grid
- `?` shows all shortcuts

## Files

- `index.html` — slide content
- `styles.css` — dark theme, color-coded track system (amber / teal / gray)
- `.nojekyll` — disables Jekyll processing on GitHub Pages
