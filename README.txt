PHASE 10 SCOREKEEPER — PERSONAL PWA

Files:
- index.html: the app
- manifest.json: installable-app metadata
- sw.js: offline cache support
- icon-192.png and icon-512.png: app icons

QUICK TEST
Open index.html in a desktop browser. Core scoring works locally. Browser local-file mode may not enable installation/offline PWA features.

FREE HOSTING WITH CLOUDFLARE PAGES (STATIC UPLOAD)
1. Sign up for a free Cloudflare account.
2. In the dashboard, open Workers & Pages and create a Pages project. If the dashboard offers direct upload, choose it.
3. Upload the contents of this folder (the files themselves should be at the site root, not nested in another folder).
4. Deploy and open the provided https://...pages.dev address.
5. On iPhone, open that address in Safari, tap Share, then Add to Home Screen.
6. Launch from the new Home Screen icon. Your scores are saved in that browser on that device.

IMPORTANT
- This is a personal prototype; there is no account sync or cloud backup.
- Browser storage can be cleared by device/browser settings. Export CSV periodically from History if you want a backup.
- Dealer rotates to the next listed player after every saved round; the Change button lets you override it.
- This is an unofficial companion and is not affiliated with or endorsed by Mattel.
