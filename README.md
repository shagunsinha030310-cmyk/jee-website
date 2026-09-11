# JEE Website PWA

Website URL configured:
https://shagunsinha030310-cmyk.github.io/jee-website/

## Upload to GitHub

Upload the **contents of this folder**, not the ZIP file itself, into your GitHub repository.

For the repository shown in your screenshot:

`shagunsinha030310-cmyk/jee-website`

Then enable GitHub Pages from **Settings → Pages → Deploy from a branch → main → / (root)**.

### Important
This is a PWA wrapper around the live website. If the website blocks being displayed inside an iframe, the wrapper will not work correctly. The best solution in that case is to add the PWA `manifest.json` and `sw.js` directly to the original website and register the service worker from its own pages.
