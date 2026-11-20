# Ventea Navidad 2026 — Interactive concept

A standalone, responsive Spanish-language fundraising page concept for Asociación Ventea. **Review prototype only** — no payments are processed, no live site is changed.

## Preview locally
Open `index.html` in a browser. No build step or dependencies are required. Google Fonts are optional; system fallbacks are provided.

## Deploy on Cloudflare Pages
1. Create a new GitHub repository (e.g. `ventea-navidad-preview`) and upload `index.html`, `styles.css`, `script.js` to the repository root.
2. In Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git, select the repository.
3. Choose a static HTML / no framework project. Build command: leave blank. Output directory: `/` (repository root).
4. Deploy and share the assigned `*.pages.dev` URL with Irene.

## Important before production
- Replace the illustrative CSS artwork with approved real imagery and Ventea branding assets.
- Validate donation wording, allocation of funds, privacy notices and any claims with Irene.
- Wire payment buttons to the correct approved Stripe links **only after review**. The prototype currently opens a demonstration modal instead of collecting payment.
- Confirm which locations and schedules can be published; four businesses are interested, not confirmed open.
- If adapting to Divi/WordPress, migrate the sections carefully and test on mobile.

## Contents
- `index.html`: page content and semantic layout
- `styles.css`: visual system and responsive styling
- `script.js`: donation selection, custom amount validation, safe demonstration modal
