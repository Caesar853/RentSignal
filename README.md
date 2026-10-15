# RentSignal — Investor Command Center (alpha prototype)

This prototype brings together rental portfolio analytics, property records, flip/renovation projects, contractor and material price tracking, a subject-to-repair financing stress test, document uploads, and appraisal/valuation history.

## Try it locally

Open `index.html` in a modern browser. The website is self-contained. For installable PWA behavior and offline app-shell caching, publish over HTTPS (for example with GitHub Pages).

## Publish free with GitHub Pages

1. Create a GitHub repository (public is simplest for free Pages on many account configurations; check GitHub's current plan rules).
2. Upload the **contents** of this folder to the repository root so `index.html`, `manifest.webmanifest`, `sw.js`, and both icons are at the root.
3. Open repository **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/(root)`, then save.
4. After GitHub publishes the site, open its HTTPS URL in Safari on your iPhone.
5. In Safari tap **Share → Add to Home Screen → Add**.

## Important prototype limitations

- Sample properties, projects, valuations, contractors, and material prices are fictional examples. Delete or replace them before using your own data.
- Data is stored in the browser's local storage on this device. There is no login, encrypted cloud database, account sharing, cross-device sync, or automatic backup. Use **Export data** to create a JSON backup.
- Uploaded files are stored as browser data and the prototype limits each attachment to 2 MB. Browser storage limits vary. Do not use this alpha for highly sensitive documents or as your only copy of important records.
- CSV property import and export are supported; review imported rows and values for accuracy.
- Bank connections, automatic APR extraction, live market comps, automated valuation models, and lender integrations are not connected. Loan APRs and valuations must be entered by the user. The financing lab is a simplified planning tool, not a lender quote or appraisal.
- GitHub Pages is public hosting for the app files. Never put personal financial data directly into source files or a public repository.
