# alejo-bosch-portfolio

Portfolio website of **Alejo Bosch**, Semi-Senior Unity Developer.

## Purpose

A static portfolio site that presents selected Unity / C# work with short video
previews. It is meant to complement a CV rather than replace it: the CV explains
the professional experience, this site demonstrates selected work.

Areas covered: gameplay programming, custom Unity tooling, performance
optimization (GPU instancing), and AR.

## Technologies used

- HTML
- CSS
- Vanilla JavaScript
- No frameworks, no build step, no dependencies

Video previews are plain HTML5 \<video\> elements loaded from the `videos/`
directory, muted and with `playsinline`, revealed on demand by a
PLAY PREVIEW / HIDE PREVIEW toggle.

## Project structure

    /
    |-- index.html          Single-page portfolio (HTML + CSS + JS inline)
    |-- videos/
    |   |-- painter.mp4
    |   |-- gpu-instancing.mp4
    |   |-- lights-board.mp4
    |   |-- mtg-timer.mp4
    |-- README.md

## GitHub Pages deployment

The site is deployed with GitHub Pages directly from the repository:

- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`

`index.html` sits at the repository root, so no build or workflow configuration
is required. Pushing to `main` redeploys the site.

Settings location: **Settings > Pages > Build and deployment**.

## Notes

- All video paths are relative (`videos/...`), so the site works both locally
  and under the GitHub Pages subpath.
- No proprietary source code, client names, or confidential assets are included
  in this repository.
