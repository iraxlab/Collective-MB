# CollectiveMB website

Luxury redesign of collectivemb.com — six pages (About, Website Developer, Video Branding, Digital Marketing, Branding Events, Contact) in one site.

## Files
- `index.html` — the website
- `support.js` — required runtime (keep next to index.html)
- `images/` — all images, compressed to WebP with descriptive SEO file names (e.g. `versace-mansion-miami-luxury-bridal-shoot.webp`), plus favicon, app icons and a 1200×630 social-share image
- `sitemap.xml`, `robots.txt`, `site.webmanifest` — search engine and browser files

## Put it online with GitHub Pages
1. Create a new repository on GitHub (e.g. `collectivemb-site`).
2. Click **Add file → Upload files** and drag in everything from this folder (index.html, support.js, robots.txt, sitemap.xml, site.webmanifest, README.md and the images folder). Delete the old `assets` folder from the repository if it is there.
3. Click **Commit changes**.
4. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
5. After about a minute the site is live at `https://<your-username>.github.io/collectivemb-site/`.

To use the real domain, add `collectivemb.com` under Settings → Pages → Custom domain and point the domain's DNS to GitHub Pages.

## Page links
- About: `/#/`
- Website Developer: `/#/website-builder`
- Video Branding: `/#/video-branding`
- Digital Marketing: `/#/marketing`
- Branding Events: `/#/events`
- Contact: `/#/contact`

## Before launch
- The contact form shows a thank-you message but does not send email yet. Connect it to a form service (e.g. Formspree) or the developer's backend.
- Isole Villa and Hilton Bali are marked "Project archived" because their links are broken; add working URLs if available.
- Opening `index.html` by double-clicking may not load everything; view it from GitHub Pages or any web server.

## After going live (SEO)
1. Add the site to Google Search Console and submit `https://collectivemb.com/sitemap.xml`.
2. Create or claim a Google Business Profile for CollectiveMB.
3. Sitemap and social-share links assume the domain collectivemb.com. If you use another domain, find-and-replace `https://collectivemb.com/` in index.html, sitemap.xml and robots.txt.
