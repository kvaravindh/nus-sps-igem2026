# AEGIS

Wiki for AEGIS, the NUS SPS iGEM 2026 project on biofilm control in the ISS
Water Processor Assembly.

Live: https://kvaravindh.github.io/nus-sps-igem2026

## What is here

`index.html` is the whole wiki: 25 sections in one self-contained file, with
every photograph, font, figure and script embedded. Nothing is fetched at run
time, so the page opens from a local copy as readily as from the web. It runs
to 42MB for that reason, and first load takes a few seconds.

The page is built against aegis-kit-v3, the team's animation and figure kit.
The kit sets the palette, the type scale, the 44 spacing unit, the SBOL
grammar for construct diagrams and the schematic style. Maths is typeset with
KaTeX at build time, so no maths engine loads in the browser.

`.nojekyll` stops GitHub Pages from running the file through Jekyll.

## Editing

Edits go to `index.html` directly. A push to `main` republishes the site.
