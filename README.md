# Hubbaly Motion Microsite

A single-file, self-contained motion and loader showcase for the Hubbaly brand
explorations. Everything — React, the WebGL field module, the fonts and every
logo — is embedded in `index.html`, so the page runs offline with no network
requests.

## Viewing

Open `index.html` in any modern browser, or use the GitHub Pages URL if Pages
is enabled on this repo.

## What's in it

Twelve scenes across both brand directions, selectable from the left nav, each
with a desktop / phone toggle:

| Group | Scenes |
| --- | --- |
| Fields | Aurora, Galaxy, Mark grid, Shine, Warp |
| Brand 2 | B2 loaders, B2 phones, B2 motion, B2 react bits |
| Brand 3 | Logo rain, B3 loaders, B3 warp |

Palettes covered: Brand 2 teal/amber/blush, Brand 2 deep teal, Brand 3 plum
night, Brand 3 flame cells. Only the visible scene runs, to keep the artwork
and the WebGL fields light.

## Build

`index.html` is a bundled export — the payload lives in `__bundler/manifest`
as gzip + base64 resources (React 18.3.1 UMD, ReactDOM, the `dc-runtime`
loader, an `ogl`-based WebGL module, five woff2 faces, and seven `.dc.html`
scene components). Edit the sources, not this file.
