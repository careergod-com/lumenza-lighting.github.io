# LUMENZA Lighting — V2

A fuller, multi-page lighting storefront built as a GitHub Pages-ready static site.

## What changed in V2
- One consistent product-card background: the image stage and product media use the same surface color.
- Product photos use `mix-blend-mode: multiply` so white studio backplates visually disappear into the card surface when remote photography loads.
- Every product also has a local deterministic SVG fallback, so the storefront never depends on a broken image URL to render.
- Expanded from the original 8-file demo into a structured multi-page project with data, modules, category assets, product pages and support content.
- Added shop filtering, sorting, cart, wishlist, product detail routes, lighting finder, smart lighting page, collections, journal, about and support.
- Header logo is sized explicitly so it cannot overlap navigation or content.

## Pages
Home · Shop · Categories · Collections · Smart Lighting · Journal · About · Support · 12 product detail pages · 404 fallback

## Structure
- `index.html` — storefront home
- `shop.html` — searchable/filterable catalog
- `categories.html` — category discovery + lighting finder
- `collections.html` — curated collections
- `smart-lighting.html` — smart lighting content
- `journal.html` — editorial content
- `about.html` — brand philosophy
- `support.html` — support/contact + FAQ
- `pages/` — individual product detail pages
- `assets/products/` — deterministic local product fallbacks
- `assets/categories/` — category visuals
- `assets/icons/` — interface icons
- `data/` — catalog, category and journal data
- `css/` — base and component styling
- `js/` — catalog, cart, wishlist, shop, finder, support and product modules

## Product image rule
The interface never places badges, prices, hearts or product names inside the product photography. Those elements belong to the HTML layer. Remote photography is optional; each product has a local fallback image.

## Technologies
HTML5 · CSS3 · JavaScript · JSON · SVG · localStorage

## Support demo
support@lumenzalighting.com · +1 (303) 555-0174 · Denver, Colorado, United States

## Status
Project in development / GitHub Pages ready.

© 2026 LUMENZA Lighting
