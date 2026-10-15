# RentSignal PWA demo

This is the current prototype packaged as a Progressive Web App (PWA). It includes an app manifest, home-screen icons, and basic offline caching.

## Publish free with GitHub Pages
1. Sign in to GitHub and create a **public** repository named `rentsignal-demo`.
2. Download and unzip `rentsignal_pwa_bundle.zip`.
3. Upload the *contents* of the `rentsignal_pwa` folder to the repository root. `index.html` must be at the root.
4. In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait for GitHub Pages to publish the site, then open the HTTPS URL it gives you in Safari on your iPhone.
6. In Safari tap **Share → Add to Home Screen → Add**.

## Important limitations
- Demo uses fictional sample data and is not suitable for real financial records.
- It does not yet have secure accounts, a cloud database, or reliable cross-device persistence.
- Offline caching makes the app shell available after first load; it does not turn demo data into synced cloud data.
- GitHub Pages free hosting and platform terms can change.
