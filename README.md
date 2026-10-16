# lilac-web

Built site for Lilac in the browser, served by GitHub Pages. Only build output lives here;
the plugin sources stay in the private repos.

- `fret/` — Lilac Fret browser test. `fret.wasm` is built from LilacFret's own
  `Source/FretEngine.cpp` via `LilacFret/web/build.sh`; `fret/index.html` is
  `LilacFret/web/index.html` wrapped in a doctype.
