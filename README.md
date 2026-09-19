# Bed & Bloom

Static-first garden calculators and practical guides. No database or backend is required.

## Run locally

From this folder, use any static server, for example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Before launch

- Replace `https://bedandbloom.example` in canonical tags, `robots.txt`, and `sitemap.xml` with the production domain.
- Add the real analytics snippet in a shared template (or each page) after creating the property.
- Add the approved AdSense script only after approval; replace the labeled `.ad-slot` areas with responsive ad units.
- Update the privacy policy to match the enabled analytics and advertising vendors.

## Cheap deployment

Deploy the folder to Cloudflare Pages, Netlify, GitHub Pages, or an object-storage static host. These pages need no server or database. A custom domain and HTTPS are the only expected fixed costs.

## Revenue paths

Clearly labeled display ads are the first monetization layer. Natural later additions include affiliate links to soil/mulch suppliers and garden tools, a printable/exportable garden plan, saved projects, and sponsored seasonal guides.
