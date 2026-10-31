# Moonwatch

Live 3D Moon tracker at **https://mymoon.live**: today's moon phase, illumination, moonrise and moonset, visibility and upcoming phases for 51 cities on every continent, in English and Thai.

- `/` and `/<city>/` – English pages, `/th/` and `/th/<city>/` – Thai pages (same app, page language and city set in `window.MW`)
- `assets/app.js`, `assets/app.css` – the shared app; `moon.jpg`, `earth.jpg` – textures; `og.jpg` – social preview
- `sitemap.xml`, `robots.txt`, `404.html`

Everything is calculated in the browser with [Astronomy Engine](https://github.com/cosinekitty/astronomy) (MIT) and drawn with [three.js](https://threejs.org) (MIT). Moon and Earth textures come from the three.js examples.
