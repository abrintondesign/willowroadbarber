# Willow Road Barber Shop

Website for Willow Road Barber Shop — Guelph's classic neighbourhood barber since the 1960s.
59 Willow Road, Guelph, ON · (519) 821-5231

Static site, no build step. Published via GitHub Pages to **willowroadbarber.ca**.

## Structure

```
.
├── index.html           # Main page
├── 404.html             # Custom not-found page
├── willow-v2.css        # All styles
├── CNAME                # Custom domain for GitHub Pages
├── robots.txt           # Crawler rules
├── sitemap.xml          # Search engine sitemap
├── wrb.jpg              # Footer logo (large)
└── images/              # Photos, videos, logo, favicon
```

## Publishing to GitHub Pages

1. Push this folder to a GitHub repo.
2. In repo **Settings → Pages**, set the source to the `main` branch, `/` root.
3. Confirm `willowroadbarber.ca` appears under Custom domain (the `CNAME` file handles this).
4. At your DNS provider, point:
   - `A` records for `willowroadbarber.ca` → GitHub Pages IPs (`185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`)
   - `CNAME` for `www` → `<your-github-username>.github.io`
5. Tick **Enforce HTTPS** in Settings → Pages once the cert provisions.

## SEO notes

- `LocalBusiness` / `BarberShop` JSON-LD schema included with full address, hours, phone, services and aggregate rating.
- Canonical URL set to `https://willowroadbarber.ca/`.
- Sitemap references the key images for Google Image indexing.
- Aggregate rating `reviewCount` is a placeholder of `100` — update it when you have the real count from Google Reviews.

## Accessibility

- Designed to WCAG 2.1 AA (AODA) standards.
- Skip-to-content link, visible focus rings, semantic landmarks.
- `prefers-reduced-motion` respected globally; autoplay videos pause for users who opt out.
- All images have meaningful alt text; decorative SVGs are `aria-hidden`.

## Local development

Open `index.html` in a browser. No build step, no dependencies.
