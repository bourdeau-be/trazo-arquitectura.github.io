# TRAZO — V2 — Architecture, Scale Models & Design Supplies

**Think in lines. Build in detail. Design with intention.**

TRAZO is a design-led storefront concept for architectural models, drafting instruments, model-making materials, landscape details and studio essentials. The experience is inspired by the workbench of an architecture studio: tactile materials, measured composition, purposeful tools and editorial storytelling.

## Brand direction

- **Graphite** for structure and technical clarity.
- **Warm ivory** for paper, studio light and model backdrops.
- **Terracotta** as a restrained accent inspired by clay, brick and material studies.
- **Editorial typography** pairing a high-contrast serif with a clean sans-serif.
- **Distinct product imagery** assigned to individual catalogue items.

## Store features

- Responsive desktop, tablet and mobile layout.
- Five visual collection cards and a twelve-item product catalogue.
- Product search, category filters and sorting by price/name.
- Shopping bag with quantity controls, subtotal and session persistence.
- Save-for-later heart controls (visual prototype state only).
- Studio journal, brand philosophy, newsletter mockup and support section.
- Local logo SVG, favicon and compressed image assets.
- Keyboard escape closes the shopping bag; mobile navigation is toggleable.
- Semantic headings, image alt text, and status messages for interactions.

## Technology

- HTML5
- CSS3 (responsive layouts, custom properties, media queries)
- Vanilla JavaScript
- SVG brand assets
- GitHub Pages-compatible static structure

## Project structure

```text
trazo-arquitectura/
├── index.html
├── README.md
├── favicon.svg
├── css/
│   └── styles.css
├── js/
│   └── main.js
└── assets/
    └── images/
        ├── trazo-logo.svg
        ├── hero-studio.jpg
        ├── categories/
        └── products/
```

## Run locally

Open `index.html` in a modern browser, or run a local server from the project root:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Upload the contents of this folder to the repository root.
2. Open **Settings → Pages**.
3. Select the `main` branch and `/ (root)` as the source.
4. Save and wait for GitHub Pages to publish.
5. Check the published page on mobile and desktop.

Expected URL, assuming owner and repository name stay unchanged:
`https://bourdeau-be.github.io/trazo-arquitectura/`

## Product prices and support

The prices in this ZIP are **illustrative USD estimates** for a storefront prototype, not verified live market quotes or inventory. Confirm supplier costs, product specs, stock, tax, shipping and final retail prices before selling. Product imagery is for design demonstration and should be replaced with verified product photography where exact product identity matters.

Contact details are placeholders:
- Email: `camille@bourdeau.be`
- Phone: `+1 (555) 014-2026`
- Example location: Portland, OR 97205 (illustrative only)

The `.example` email domain is reserved for examples and is not a working mailbox. Replace all support details before launch. No payment processor, order backend, inventory, accounts, or email collection service is connected.

## Quality checks completed

- ZIP archive integrity check.
- Local image, CSS and JavaScript paths checked.
- Product data references twelve separate image files.
- Image dimensions and file sizes checked.
- Responsive breakpoints included for tablet and mobile widths.

A static validation pass cannot guarantee flawless rendering in every browser; preview the actual GitHub Pages deployment before launch.

## Roadmap

- [ ] Replace demonstration image crops with licensed, product-specific photography.
- [ ] Verify actual supplier prices and product specifications.
- [ ] Replace placeholder support contact details.
- [ ] Add secure checkout, order management and stock integration if required.
- [ ] Connect newsletter signup to a consent-based email service.
- [ ] Test on real mobile devices and major browsers.

## Status

**Project in development — static storefront prototype.**

## License

No license is included. All rights not expressly granted are reserved. Add an appropriate license only after reviewing ownership and usage rights for every source asset.

© 2026 TRAZO — Architecture, Scale Models & Design Supplies. All rights reserved.
