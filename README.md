# NORTE — Cartography & Adventure

**Find your direction. Explore beyond.**

NORTE is an outdoor cartography and adventure storefront concept for hikers, travelers, route planners, and curious explorers. It brings together navigation tools, topographic-style maps, trail essentials, and thoughtfully selected outdoor accessories in a calm, editorial shopping experience.

## Brand philosophy

Every journey begins with a direction. NORTE pairs the timeless language of maps, compass roses, contour lines, and mountain landscapes with a practical modern storefront.

**Brand palette:** forest green, warm cream, sand, and expedition orange.

## Collections

- **Maps & Cartography:** topographic-style map sets, map cases, and field notebooks
- **Navigation:** compass and handheld GPS concepts
- **Packs & Bags:** daypacks and gear organizers
- **Hiking Gear:** trekking poles and rain layers
- **Lighting & Safety:** headlamp, first-aid pouch, and safety whistle
- **Hydration:** insulated trail bottle
- **Exploration Tools:** compact binoculars
- **Power & Lighting:** solar power bank and camping lantern

## Features

- Responsive layouts for desktop, tablet, and mobile
- 16-item product catalog stored in local JSON
- Product images stored locally and assigned individually
- Live search, category filtering, and sorting
- Product detail dialog
- Shopping bag with quantity controls and subtotal
- Saved items/favorites
- Browser storage for cart and favorites where available
- Newsletter demo interaction
- Local logo and favicon
- GitHub Pages-compatible static structure

> **Demo storefront:** the catalog uses realistic illustrative prices informed by common outdoor-retail price ranges. These are not guaranteed live offers for the exact pictured products. Product photos are generated visual concepts and do not depict verified retail SKUs. Checkout, payment processing, shipping rates, inventory, customer accounts, and email delivery are not connected.

## Price references

Prices were reviewed against public outdoor retail listings on October 13, 2026 and can change:

- REI lists the Suunto A-10 NH Compass at $28 and the Suunto MC-2 NH Mirror Compass at $70: https://www.rei.com/c/compasses
- Philmont Scout Ranch lists several compasses, waterproof map cases, and 2026 sectional maps at prices spanning roughly $8 to $45: https://store.philmontscoutranch.org/camping-hiking-gear/gadgets-tools/navigation/
- WorldHike's 2026 backpacking gear price index reports current listing examples for categories such as trekking poles, headlamps, packs, and water filters: https://worldhike.org/journal/backpacking-gear-weight-index

These sources are price benchmarks only; NORTE is a concept storefront and is not affiliated with those retailers or brands.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- JSON catalog data
- GitHub Pages static hosting

## Project structure

```text
norte-adventure/
├── index.html
├── README.md
├── css/
│   └── styles.css
├── js/
│   └── app.js
└── assets/
    ├── data/
    │   └── products.json
    ├── images/
    │   ├── hero-adventure.jpg
    │   ├── favicon.jpg
    │   └── products/
    │       └── 16 individual product photos
    └── logo/
        └── norte-logo.jpg
```

## Run locally

The catalog is loaded with `fetch()`, so use a local server rather than opening the HTML directly with a `file://` URL.

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Upload the complete project contents to the root of the `norte-adventure` repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`.
5. Save and wait for the site to publish.

The URL usually follows `https://YOUR-USERNAME.github.io/norte-adventure/`. Replace `YOUR-USERNAME` with your GitHub username.

## Quality checklist

- [x] Local logo and favicon included
- [x] Hero image stored locally
- [x] 16 individual product image files
- [x] Catalog JSON validates
- [x] Image paths assigned explicitly per product
- [x] Search, filter, and sort controls implemented
- [x] Product detail dialog implemented
- [x] Cart quantity and subtotal logic implemented
- [x] Favorites and browser persistence implemented
- [x] Responsive desktop and mobile layouts
- [x] Local asset references checked
- [x] ZIP archive integrity checked
- [ ] Connect a real checkout/payment provider
- [ ] Confirm real SKUs, specifications, stock, and commercial pricing
- [ ] Replace placeholder support address with an official inbox

## Customer support

**NORTE — Cartography & Adventure**  
Support placeholder: `support@norte.example`

The `.example` address is reserved for documentation and is not a live inbox. Replace it with an official support address before using this storefront commercially.

## Project status

**Status: In development.** This is a functional frontend demonstration. Real commercial launch requires verified product data and any required third-party integrations.

## License

No open-source license has been selected. All rights not expressly granted remain reserved.

---

**NORTE — Find your direction. Explore beyond.**

© 2026 NORTE Cartography & Adventure. All rights reserved.
