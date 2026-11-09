# Zephy’s Art Gallery

The website at [zephyartgallery.com](https://zephyartgallery.com), served by GitHub Pages from the `main` branch.

## What's where

- `index.html` is the whole site: layout, styles and script in one file.
- `img/` holds the artwork photos, two sizes each (`-<width>.jpg`).
- `CNAME` tells GitHub Pages to serve the site on zephyartgallery.com.

## Common edits (all in the script near the bottom of `index.html`)

- **Titles, prices, sizes, descriptions:** the `WORKS` list. Sizes are width × height in cm.
- **Sold or reserved:** set a work's `status` to `"sold"` or `"reserved"`. Sold works get the red dot.
- **Contact options:** `CONTACT` (WhatsApp, email, Instagram, TikTok).
- **PayPal:** put the PayPal.Me name in `PAYPAL_ME` to show “Pay with PayPal” buttons with each price filled in.
- **Order on the hero wall:** the `WALL` list.

Every push to `main` updates the live site within a few minutes.
