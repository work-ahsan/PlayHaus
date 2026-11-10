# PLAYHAUS — Toy Store Showcase

Built by redesigning the supplied `ecommerce-store.zip` storefront concept for toy shop owner meetings. The original e-commerce site's key ideas (animated hero, product browsing, search, quick view, wishlist, cart, checkout preview) are retained and reimagined around a unique, playful toy-store identity.

## Run the website (Linux Mint / Windows / Mac)

This version is completely self-contained, with **no npm, React build, or internet connection required**.

1. Extract the ZIP.
2. Open the `Playhaus_Toy_Store` folder in VS Code.
3. Run `python3 -m http.server 8765` in its terminal.
4. Visit `http://localhost:8765`.

Alternatively, open `index.html` directly in a browser. Open `image-check.html` to test all 16 images independently. To avoid seeing a cached older demo, use the new folder name and port 8765.

## Features

- Responsive premium toy shop landing page with parallax effects, floating photo tiles, custom category cards, animated ticker, scroll reveals.
- 16 toy sample images **actually bundled** in `images/toys/*.webp`. **No external image links**.
- Shop categories, search, sorting, quick product detail dialogs, age and budget gift finder.
- Wishlist, cart with quantities, persistent browser storage, simulated checkout.
- Working mobile menu, keyboard Escape to close dialogs, accessible controls and reduced-motion support.

## Important

This is a **fictional showcase**, not a functioning retail business. Products and PKR prices are illustrative. Product imagery is **AI-generated photorealistic sample imagery**, not photographs of any toy shop's actual stock. The checkout and newsletter are local simulations: no payments or emails are processed.

## Files

- `index.html` — all store sections and interactive shells
- `styles.css` — styling, animation, mobile responsiveness
- `app.js` — catalog, search, filters, cart, wishlist, gift finder, demo checkout
- `images/toys/` — 16 local WebP toy images
