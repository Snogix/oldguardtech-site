# oldguardtech-site

Static site for **https://oldguardtech.ca**, served by GitHub Pages from `main` / root.

- Plain HTML + one stylesheet (`assets/css/site.css`). No build step, no JavaScript, no cookies.
- Copy source of truth: the vault note `02-Projects/Marketing and Positioning/Website Copy.md`.
- DNS lives at DreamHost (domain set to DNS Only): apex A/AAAA → GitHub Pages, `www` CNAME → `snogix.github.io`.
  Microsoft 365 mail records (MX, SPF, DKIM, autodiscover, DMARC) are also in that zone — leave them alone.

## Rules for edits

- **No prices** anywhere on the site. Pricing goes in proposals.
- **No former employer named.**
- Contact is `info@oldguardtech.ca` only.
- Header and footer are repeated in each page — change all five HTML files together.
