# Vexus Grocery Store

A responsive, static e‑commerce website for a grocery store. Built with HTML, CSS, and JavaScript (jQuery + Bootstrap), featuring category pages, product listings, a mini cart demo, and a simple checkout flow.

## Highlights
- Responsive layout using Bootstrap.
- Category pages: `bakery products`, `bread`, `drinks`, `frozen`, `household`, `pet`, `vegetables`, plus `products`, `checkout`, `about`, `login`, and `contact` (`mail.html`).
- Product cards with images and basic interactions.
- Mini cart demo via `minicart.js` (client-side only, no real payments).
- Image zoom (`okzoom`), sliders (`flexslider`), smooth scrolling, and animation utilities (`waypoints`, `counterup`).

## Tech Stack
- HTML5, CSS3, JavaScript (ES5/ES6 where applicable)
- Bootstrap, Font Awesome (local assets)
- jQuery, Flexslider, Waypoints, CounterUp, OkZoom, Minicart

## Project Structure
```
Vexus-Grocery-Store/
├── index.html               # Home page
├── about.html               # About page
├── products.html            # All products listing
├── checkout.html            # Mini cart & checkout demo
├── login.html               # Login (static)
├── mail.html                # Contact (static)
├── vegetables.html          # Category pages (examples below)
├── bakery products.html
├── bread.html
├── drinks.html
├── frozen.html
├── household.html
├── pet.html
├── css/
│   ├── bootstrap.css
│   ├── flexslider.css
│   ├── font-awesome.css
│   └── style.css            # Main site styles
├── js/
│   ├── jquery-1.11.1.min.js
│   ├── bootstrap.min.js
│   ├── jquery.flexslider.js
│   ├── jquery.wmuSlider.js
│   ├── minicart.js
│   ├── counterup.min.js
│   ├── waypoints.min.js
│   ├── easing.js
│   ├── move-top.js
│   └── okzoom.js
└── images/                  # Product and UI images
```

## Quick Start
- Local: open `index.html` in any modern browser.
- Optional: use a lightweight HTTP server for best results (e.g., VS Code Live Server or `npx serve`).

### Run locally (examples)
- VS Code: install "Live Server" → right‑click `index.html` → "Open with Live Server".

## Customization
- Styles: edit `css/style.css` and `css/bootstrap.css` as needed.
- Scripts: update plugin behavior in `js/` files or add your own JS.
- Images: replace assets in `images/` with your brand visuals.
- Pages: duplicate category HTML files to add new departments.

## Notes & Limitations
- Cart and checkout are client-side demos; there is no backend or real payment integration.
- For production, integrate a server and payment provider (e.g., Stripe) and validate inputs.