# UWM TRANSLATE unified prototype — original-theme edition

This version deliberately reuses the visual language of the original UWM TRANSLATE prototype:
large RESEARCH TO IMPACT hero, pastel icon bubbles, rounded cards, Discover→Develop→Connect→Translate→Change pathway, and the original published research-to-impact SVG.

## Structure
- `/index.html` — static UWM TRANSLATE landing page
- `/os/` — living Research Translation Operating System portal
- `/assets/styles.css` — shared theme

## Important note about the hero graphic
The hero references the original graphic already published in your existing repository:
`https://ivastgit.github.io/uwm-translate-prototype/assets/graphic.svg`
This ensures the exact original illustration is used. If you later copy `graphic.svg` into this package's `/assets/` folder, change the image source in `index.html` to `assets/graphic.svg` and the site will be fully self-contained.

## GitHub Pages
Upload the contents of this folder to the repository root. Enable Settings → Pages → Deploy from branch → main → /(root).
