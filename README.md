# Made2Sell

Landing page for **Made2Sell** — offline inventory, costing and sales tracking for
hobby crafters and craft-fair sellers (the app is built from the
[EasyCommerce.Flutter](https://github.com/Agrabski/EasyCommerce.Flutter) codebase).

The page gives a concrete value proposition and a screenshot-driven tour of every
major feature: the dashboard and financial trends, product costing (materials +
labour, margin, suggested price), materials with recipe-based stock and custom
types, the plan → pack → sell → results fair workflow, the fast sale-mode till,
custom orders and customers, expenses, product-performance reports, and the
seller profile / settings (branding, themes, language, local backup).

## Features

- Bilingual: English / Polish toggle that swaps both copy **and** the app screenshots
- Screenshot-driven feature tour using real captures from the app
- Responsive, mobile-first layout with light/dark support
- Sage-green theme matching the app's own Material 3 look
- Honest "closed alpha / Android-only" framing with an email call-to-action
- Pricing section: free, no ads, donations (future) and possible future paid
  retailer integrations

## Assets

App screenshots live in `images/en/` and `images/pl/` (phone captures sourced from
`store_assets/screenshots/phone/` in the EasyCommerce.Flutter repo). File names match
across both language folders so the toggle can swap them by path prefix.

## Hosting

Hosted on GitHub Pages at `https://agrabski.github.io/made2sell`.

## Local Development

Open `index.html` in a browser to preview locally. To update, edit `index.html`
(all CSS/JS is inlined, no build step) and push to the `main` branch.
