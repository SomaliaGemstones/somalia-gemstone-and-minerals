# Somalia Gemstone & Minerals

Welcome! This repository contains a small static website for Somalia Gemstone & Minerals. The site helps with basic gemstone identification, testing information, and market support resources.

Why this repo
- A simple, accessible, and SEO-ready static site you can host anywhere (GitHub Pages, Netlify, Vercel).
- Easy to customize: swap images, update contact links, or add a contact form.

What’s included
- Accessible HTML with a skip link, clear headings, and focus styles.
- SEO & social metadata (Open Graph, Twitter card, JSON-LD).
- Styles moved to `css/style.css` for easier maintenance.
- A basic image gallery (replace images in `/images`).
- Phone and WhatsApp contact links and a tiny JS script to keep the year current.

Quick preview locally
1. From the repo root run:
   - Python 3: `python -m http.server 8000`
2. Open http://localhost:8000 in your browser.

Images to add or replace
- /images/hero-gem.jpg
- /images/gem-1.jpg
- /images/mineral-1.jpg
- /images/test-1.jpg
- /images/logo.png (used for social previews / favicon)
- /images/og-image.jpg (Open Graph preview)

Tips
- Optimize images (WebP or AVIF where possible) and add responsive `srcset` or `<picture>` for different screen sizes.
- Inline a small amount of critical CSS for the top of the page to improve first paint. Keep the rest in `css/style.css`.
- If you need to collect inquiries, add a simple contact form or use a serverless provider (Formspree, Netlify Forms).
- Run Lighthouse and an accessibility (axe) audit to catch improvements. I can run these and give a short report.

Contributing or help
- Want me to commit this README directly and open a PR? I already applied this update.
- I can also:
  - Replace or optimize images for the site.
  - Add a contact form and serverless handling.
  - Set up a GitHub Actions workflow to preview the site.
  - Run Lighthouse / axe and send a short report with fixes.

License
- Add a LICENSE file if you want to set the project license (MIT is a common choice).

Thanks — if you want more improvements (contact form, CI, image optimization), tell me which and I’ll implement them and open a PR.
