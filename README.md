# Krishna Pinnamaneni canonical homepage

Static personal profile site for Krishna Pinnamaneni.

Published URL: <https://krishn1232427.github.io/krishna-pinnamaneni-site/>

## Files

- `index.html` - the homepage content, metadata, structured data, FAQ, and
  primary portfolio directory.
- `brand.html` - profile, bio, highlights, and work summary.
- `advisory.html` - board/advisory positioning for AI, commerce, privacy,
  product strategy, and local-first software.
- `apps-books-plugins.html` - portfolio catalog page for apps, 12 technical
  books, browser extensions, Chrome apps, and plugins.
- `styles.css` - the visual system and responsive layout.
- `assets/` - copied local app icons and book cover artwork used by the page.
- `favicon.svg` and `site.webmanifest` - browser identity files.
- `404.html` - static-host fallback page.
- `robots.txt` - basic crawler allowlist.
- `sitemap.xml` - URL list for search crawlers.
- `llms.txt` and `llms-full.txt` - AI-readable profile and catalog summaries.
- `ai-index.json` and `catalog.json` - machine-readable profile, app, technical
  book, and browser-tool data.

## Deployment notes

This can be hosted as plain static HTML on GitHub Pages, Cloudflare Pages, Netlify,
Vercel, or any basic web host. If deploying to a custom personal domain, update
the canonical URL and Open Graph URL in `index.html`.

The site separates Krishna's PayPal work from independent apps and books in the
public copy.

## Pre-deploy checklist

- Replace any placeholder domain metadata with the final personal domain.
- Add a `CNAME` file only if deploying to GitHub Pages with a custom domain.
- Keep the `qa/` folder out of deployment if local screenshots are generated.
- Re-run a mobile and desktop browser check after changing copy or assets.
