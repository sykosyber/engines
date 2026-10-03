# Engines

Selected procedural engines by Mateo at SyberLabs, with a self-portrait by Claude.

Each engine is a single self-contained HTML file in `works/`, using Canvas 2D or WebGL2 and no libraries. `index.html` is the portfolio page; every work can be run live from it, or opened directly.

| Work | File | Renderer |
|---|---|---|
| Ostensoria | `works/ostensoria.html` | Canvas 2D |
| Gyre | `works/gyre.html` | Canvas 2D |
| Interferentia | `works/interferentia.html` | WebGL2 |
| Vestigia | `works/vestigia.html` | Canvas 2D |
| Civitas | `works/civitas.html` | Canvas 2D |
| Sophia | `works/sophia.html` | Canvas 2D |
| Interpres | `works/interpres.html` | Canvas 2D |

## Running locally

Open `index.html` through any static server, for example `python3 -m http.server`, then visit `http://localhost:8000`.

## Publishing

The site is static. With GitHub Pages enabled on the `main` branch (root folder), it is served at `https://sykosyber.github.io/engines/`.
