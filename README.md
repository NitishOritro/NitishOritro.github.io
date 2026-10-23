# Nitish Ranjan Bhowmik — Personal Website

Single-page portfolio: no build step, no framework. Everything lives in `index.html`
(hand-written CSS + vanilla JS) with `profile1.jpg` as the only asset.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```sh
python -m http.server 8000
# → http://localhost:8000
```

## Hosting

Served free by GitHub Pages from the `NitishOritro.github.io` repository:

**https://nitishoritro.github.io/**

Pages is configured under **Settings → Pages** (Source: *Deploy from a branch*,
branch `main`, folder `/ (root)`). Every `git push` to `main` redeploys
automatically within a minute or two.

## Editing content

All content is plain HTML in `index.html`, grouped by section
(`#about`, `#experience`, `#education`, `#publications`, `#skills`,
`#projects`, `#certifications`, `#achievements`, `#contact`).
Copy an existing card/article block to add a new entry.

Colours and fonts are CSS variables at the top of the `<style>` block
(`:root` for light mode, `:root[data-theme="dark"]` for dark mode).
