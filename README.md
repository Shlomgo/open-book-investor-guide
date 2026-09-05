# Open Book Investor Guide

Standalone review prototype for Mia Shlomit Gordon's rental-property investor experience.

This repository is intentionally separate from the production portfolio site.

## How it is connected to the production site

The prototype reuses the current Open Book brand assets and theme CSS from `portfolio-web-page` and loads that site's `property-data.csv` in the browser. This keeps the full portfolio ledger and the proposed-deal selector aligned with the production data without maintaining a second copy of the table.

Current property-detail links continue to open the production property pages.

## Files

- `index.html` — the complete guided investor experience
- `.github/workflows/pages.yml` — optional GitHub Pages deployment workflow

The production repository itself is not modified by this prototype.
