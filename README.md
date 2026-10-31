# Dr Prabu Rau Neurosurgery Clinic website

Static site (single `index.html`). Hosted on Netlify from this repo, no build step.

## Before launch
- In `index.html`, find the settings block at the top of the script and fill in `WA_NUMBER`, `PHONE`, `W3_KEY` (Web3Forms access key) and `MAP_QUERY`.
- Set `LOCK_ENABLED = false` once Dr. Prabu approves the site, then remove the under-construction ticker.
- Remove `<meta name="robots" content="noindex,nofollow">` and delete `robots.txt` so search engines can index the site.
- Replace the "To confirm" placeholders (qualifications, address, phones, hospitals, hours).
