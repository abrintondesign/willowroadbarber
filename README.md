# Smith-Dobrowsky Real Estate Team Site

Modern static marketing site rebuild for a Burlington / Hamilton real estate team.

## Proposed file structure

```text
.
├── index.html
├── buyers.html
├── sellers.html
├── listings.html
├── about.html
├── contact.html
├── blog.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── site.js
├── components/
│   ├── header/
│   │   └── header.html
│   ├── hero/
│   │   └── hero.html
│   ├── trust-strip/
│   │   └── trust-strip.html
│   ├── service-cards/
│   │   └── service-cards.html
│   ├── listings-grid/
│   │   ├── listings-grid.html
│   │   └── property-card.html
│   ├── testimonial-slider/
│   │   ├── testimonial-slider.html
│   │   └── testimonial.html
│   ├── market-insights/
│   │   └── market-insights.html
│   ├── cta-section/
│   │   └── cta-section.html
│   └── footer/
│       └── footer.html
├── robots.txt
├── sitemap.xml
└── 404.html
```

## Notes

- Static HTML, CSS, and JS with no build step.
- Shared styles and interactions live under `assets/`.
- `components/` contains reusable reference snippets for future page assembly or CMS migration.
- Representative content is tailored to Burlington, Hamilton, and surrounding Ontario markets.
