# Supreme Pool & Snooker Club Website

This is a premium single-page website for Supreme Pool & Snooker Club, Bhilai.

## Files
- `index.html` — complete website with HTML, CSS, and JavaScript in one file.
- `assets/gallery/` — folder prepared for your original photos.

## How to add original photos manually
Open `index.html` and search for `gallery-placeholder` or `Gallery Section`.

You can replace any placeholder block with an image like this:

```html
<img src="assets/gallery/pool-table.jpg" alt="Supreme Pool & Snooker Club pool table">
```

Recommended photo names:
- `assets/gallery/pool-table.jpg`
- `assets/gallery/snooker-table.jpg`
- `assets/gallery/interior.jpg`
- `assets/gallery/players.jpg`
- `assets/gallery/coffee.jpg`
- `assets/gallery/cues-balls.jpg`

## How to edit prices/offers
In `index.html`, search for:
- `const pricing = [`
- `const offers = [`

Edit the names, prices, and descriptions there.

## WhatsApp booking number
Current number: +91 95892 63332

To change it, search for:

```js
const PHONE = '919589263332';
```

## Hosting
Upload the full folder to any static hosting service such as Netlify, Vercel, GitHub Pages, cPanel, Hostinger, or GoDaddy hosting.
