# FORME. — Home & Living e-commerce concept

**Original front-end e-commerce portfolio project by Ifeoluwa Ojo**  
A warm, editorial, responsive homewares storefront with working shopping interactions.

## What is this?

FORME. is a **fictional** online home and living brand, created to demonstrate front-end design, UI development and browser-side shopping flows. It is not a real store; products, photos, prices and shipping amounts are illustrative. The checkout does not collect payments, place real orders or send form information to a server.

## Features

- Responsive home page, category browsing and editorial brand story
- 12 demo products across Furniture, Décor, Lighting, Textiles and Botanicals
- Live product search, category chips, price range and sorting
- Individual product pages with product images, detail sections and quantity selection
- Save/remove favourites and view just the saved collection
- Shopping bag drawer, add/remove/adjust quantity, automatically calculated totals
- Browser `localStorage` persistence for cart, favourites and discount state
- UK £ prices, illustrative shipping calculations and discount code `WELCOME10`
- Demo checkout with built-in form validation and browser-only confirmation state
- Accessible semantic HTML and keyboard controls, visible focus states, reduced-motion support
- Original, locally bundled product imagery based on generated editorial concept artwork
- No backend, npm, API key, payment service or paid hosting required

## Pages

| Page | File |
| --- | --- |
| Landing page | `index.html` |
| Full catalogue | `shop.html` |
| Individual product | `product.html?id=haven-chair` |
| Fictional brand story / project details | `story.html` |
| Non-payment demo checkout | `checkout.html` |

## Run locally

Extract the ZIP and open `index.html` in a modern web browser. Links, images, cart and browser storage should work from the same folder. Alternatively run a local static server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

The headings use Google Fonts when available and system/Georgia fallbacks when offline. All *product images* are stored locally in the `assets/images` folder.

## Publish on GitHub Pages — IMPORTANT

1. On your GitHub profile `ifeoluwaojo-dev`, choose **New repository**.
2. Name it `forme-home-living` and set it to **Public**.
3. Open the new repo, choose **Add file → Upload files**, and upload **all extracted contents** of this ZIP (not the ZIP itself). Keep `index.html` at the repository root, next to `shop.html`, `product.html`, `story.html`, `checkout.html`, and the `assets` folder.
4. Click **Commit changes**.
5. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, **main**, and **/(root)**, then **Save**.
6. Once the Pages deployment succeeds, your live link should be:

   `https://ifeoluwaojo-dev.github.io/forme-home-living/`

**Do not upload this project over your existing `github.io` portfolio root.** It is intended for its **own repository** so both projects remain available.

## Add this project to your portfolio

**Title:** FORME. — Home & Living E-commerce Store  
**Role:** Independent front-end development project  
**Stack:** HTML5, CSS3, vanilla JavaScript, localStorage, responsive design  
**Description:** Designed and developed a responsive homewares e-commerce demo featuring category filtering, search, wishlist management, persistent shopping cart, individual product detail pages, and a simulated checkout flow with promotional code support.  
**Live demo (after publication):** `https://ifeoluwaojo-dev.github.io/forme-home-living/`  
**Source code (after publication):** `https://github.com/ifeoluwaojo-dev/forme-home-living`

A separate portfolio-update ZIP may be provided. If so, **publish this storefront first**, then upload the portfolio update to your existing `github.io` repository.

## Demo functionality and privacy

The promo code `WELCOME10` applies an illustrative 10% discount. Shipping is simulated as £6.50 when the basket is below £150, otherwise £0. The checkout form does **not** transmit addresses, names or emails; only an anonymous dummy order reference and amount are saved locally to display the simulated confirmation screen. Cart and favourite choices are saved only in the visitor's browser, and can be cleared by clearing site data.

There is no login, user account system, payment gateway, inventory management or order processing. These would require server-side work and secure integrations before this could be a real commerce business.

## Project structure

```
forme-home-living/
├── index.html
├── shop.html
├── product.html
├── story.html
├── checkout.html
├── assets/
│   ├── css/styles.css
│   ├── js/app.js
│   ├── images/*.webp
│   └── favicon.svg
├── .nojekyll
└── README.md
```

© 2026 Ifeoluwa Ojo. A fictional demo; not affiliated with an existing retailer.
