# Krishna Pinnamaneni canonical homepage

Static personal homepage for Krishna Pinnamaneni.

Published URL: <https://krishn1232427.github.io/krishna-pinnamaneni-site/>

## Files

- `index.html` - the page content and SEO metadata.
- `styles.css` - the visual system and responsive layout.
- `assets/` - copied local app icons and book cover artwork used by the page.
- `favicon.svg` and `site.webmanifest` - browser identity files.
- `404.html` - static-host fallback page.
- `robots.txt` - basic crawler allowlist.

## Deployment notes

This can be hosted as plain static HTML on GitHub Pages, Cloudflare Pages, Netlify,
Vercel, or any basic web host. If deploying to a custom personal domain, update
the canonical URL and Open Graph URL in `index.html`.

The page separates Krishna's PayPal work from independent apps and books in the
hero note.

## Pre-deploy checklist

- Replace any placeholder domain metadata with the final personal domain.
- Add a `CNAME` file only if deploying to GitHub Pages with a custom domain.
- Keep the `qa/` folder out of deployment if local screenshots are generated.
- Re-run a mobile and desktop browser check after changing copy or assets.
