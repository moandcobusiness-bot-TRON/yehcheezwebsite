# Yeh Cheez! website

Static site for Yeh Cheez! (Pakistani eatery, Milton ON). No build step: `index.html` + `images/` + `sw.js`.

## Edit your details
Open `index.html` and edit the `SITE = { ... }` block near the bottom (phone, social links, delivery link, map coordinates).
After changing files, bump `VERSION` in `sw.js` so returning visitors get the update.

## Preview locally
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000.

## Hosting
Served by GitHub Pages from this branch's root (Settings → Pages → Deploy from a branch).
