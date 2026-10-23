# Nitish Ranjan Bhowmik — Personal Website

Single-page portfolio: no build step, no framework. Everything lives in `index.html`
(hand-written CSS + vanilla JS) with `profile1.jpg` as the only asset.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```sh
python -m http.server 8000
# → http://localhost:8000
```

## Free hosting on GitHub Pages

1. Push this repository to GitHub (e.g. `NitishOritro/nitish.ranjan`).
2. On GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)** → **Save**
3. After a minute the site is live at
   `https://nitishoritro.github.io/nitish.ranjan/`

To get the shorter `https://nitishoritro.github.io/` URL instead, rename the
repository to `NitishOritro.github.io`.

Every `git push` to `main` redeploys automatically.

## Editing content

All content is plain HTML in `index.html`, grouped by section
(`#about`, `#experience`, `#education`, `#publications`, `#skills`,
`#projects`, `#certifications`, `#achievements`, `#contact`).
Copy an existing card/article block to add a new entry.

Colours and fonts are CSS variables at the top of the `<style>` block
(`:root` for light mode, `:root[data-theme="dark"]` for dark mode).
