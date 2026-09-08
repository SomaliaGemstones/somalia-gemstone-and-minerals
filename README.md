# Somalia Gemstone and Minerals

This repository contains a small static website for "Somalia Gemstone and Minerals" offering gemstone identification, testing, and market support.

What I updated

- Improved accessibility and semantics (skip link, ARIA roles, headings, focus styles).
- Added SEO and social metadata (Open Graph, Twitter card, JSON-LD Organization).
- Moved styles into `css/style.css` for better caching and maintainability.
- Replaced placeholder gallery placeholders with <img> elements (add your optimized images under `/images`).
- Added telephone and WhatsApp contact links, and small JS to display the current year.

Files to replace or add

- `index.html` — updated and links to `css/style.css`.
- `css/style.css` — moved CSS here.
- `README.md` — this file.

Next recommended steps

1. Replace images in `/images`:
   - `/images/hero-gem.jpg`
   - `/images/gem-1.jpg`
   - `/images/mineral-1.jpg`
   - `/images/test-1.jpg`
   - `/images/logo.png` (used for social previews)
   - `/images/og-image.jpg` (used for Open Graph)

   Optimize images (WebP/AVIF where supported), add `srcset` and `picture` elements for responsive sources.

2. Move small critical CSS inline (if you need faster first paint) and defer the rest by keeping `link rel="stylesheet"`.

3. Add a simple contact form or serverless form endpoint (Formspree, Netlify Forms) if you want to collect inquiries on the site.

4. Run Lighthouse and an accessibility audit (axe) and fix any remaining issues. I can run these and provide a short report.

How to preview locally

- From the repo root:
  - Python 3: `python -m http.server 8000`
  - Then open http://localhost:8000 in your browser.

Contributing

If you'd like more changes (move to a feature branch, add CI, or add a contact form), tell me which and I will implement them and open a PR.