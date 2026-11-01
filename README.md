# BUOY ASAP

Storefront and scroll story for BUOY ASAP, handmade cold-process soap from Chennai.

Design and build: [mathewthomas.design](https://mathewthomas.design)

## What's here
- `index.html`: the whole site in one file: hash-routed views (home, shop, product, Custom Bars, story, help, ingredients, checkout, orders, admin), GSAP + Lenis scroll scenes, and two WebGL scenes (the Indulge oil and the Custom Bars stage).
- `img/`: photography and cut-outs.
- `seq/how/`: the "How a bar is made" footage as 129 WebP frames (desktop `d/`, phone `m/`).

## Running it
Open `index.html` through any static server (for example `npx serve .`). It is also ready for GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.

Outside claude.ai the live shop database isn't available, so the site runs in browse mode: every bar, page and animation works from a built-in catalogue, and ordering shows "Ordering isn't available in this preview."
