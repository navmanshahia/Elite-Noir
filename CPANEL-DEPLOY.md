# cPanel deployment

This branch builds the Elite Noir source on GitHub, so Node/npm is not required on Namecheap.

## Recommended
1. Open GitHub Actions > Build production package.
2. Open the latest successful run.
3. Download the **elite-noir-production** artifact.
4. Extract **elite-noir-production.zip**.
5. Upload/extract the contents directly into `public_html/`.

The production package contains only the Elite Noir root frontend (`index.html`, `assets/`, and `.htaccess`). It does not contain or delete Telecom, TripFlow, TCF Monitor, or other existing application folders.

## Important
Portal destinations are configured in `src/sites.js`. Telecom is configured. Replace the remaining placeholder URLs before final launch.
