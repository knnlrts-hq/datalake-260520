# Trax Analytics — The Reset

A reveal.js presentation laying out the short-term / medium-term / long-term action plan to reset the Payment Hub analytics initiative around the Logi license expiry in **June 2027**.

## View it

- **Locally:** open `docs/index.html` in any modern browser, or
  ```bash
  cd docs && python3 -m http.server 8000
  # then visit http://localhost:8000/
  ```
- **Hosted on GitHub Pages:** see the configuration step below.

## Deploy to GitHub Pages

1. Push this branch to GitHub.
2. In the repository: **Settings → Pages**.
3. Under **Build and deployment**:
   - **Source:** `Deploy from a branch`
   - **Branch:** `claude/datalake-recap-presentation-ARN72` (or `main` after merge), folder `/docs`
4. Save. The deck will be live at `https://<org>.github.io/<repo>/` within a minute.

The `.nojekyll` file ensures GitHub Pages serves the files literally (no Jekyll preprocessing).

## Structure

- `docs/index.html` — the 33-slide deck (reveal.js loaded from CDN)
- `docs/styles.css` — custom dark theme (IBM Plex, amber/teal palette)
- `docs/.nojekyll` — disables Jekyll processing for GitHub Pages

## Navigating the deck

- **Arrow keys** or **space** — advance / go back
- **Esc** — overview mode (zoom out to all slides)
- **F** — fullscreen
- **S** — speaker notes (currently none)
- The URL hash updates per slide so any slide is directly linkable.
