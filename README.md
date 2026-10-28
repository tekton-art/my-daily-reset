# My Daily Reset — iPhone PWA

A free, phone-friendly Progressive Web App (PWA) for the six morning habits, custom habits, 7/14/21-day challenges, progress graphs, streaks, and daily reflections.

## What is included
- `index.html` — the complete app
- `manifest.webmanifest` — app name, colors, and Home Screen display settings
- `sw.js` — basic offline cache
- `icon-192.png`, `icon-512.png` — app icons

## Easiest free install on iPhone: GitHub Pages
A PWA needs an HTTPS website address for service-worker/offline support. You can host this project free on GitHub Pages.

1. On a computer or iPhone browser, sign in or create a free account at https://github.com/.
2. Create a new **public** repository named `my-daily-reset`.
3. Upload all five files from this folder to the repository root. (Keep filenames exactly as they are.)
4. In the repository, open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. The URL will look like `https://YOUR-USERNAME.github.io/my-daily-reset/`.
7. Open that URL in **Safari** on your iPhone.
8. Tap **Share → Add to Home Screen**. If shown, enable **Open as Web App**, then tap Add.
9. Launch **My Daily Reset** from the new Home Screen icon.

GitHub's menu labels may change slightly. If Pages does not appear, confirm the repository is public and the files are in the repository root.

## Local storage and backups
- The app stores habits, check-ins, challenge settings, and reflections in this browser on this device. It has no account and sends no tracking data to a server.
- Use **Export backup** periodically and save the JSON file somewhere safe.
- Use **Import backup** to restore a JSON backup.
- Clearing Safari website data, using another browser, or removing app/site data may erase the local data. A web app's local storage is not a substitute for a cloud backup.
- Offline caching is best-effort; first open the app online after publishing so the files can be cached.

## Editing the app
You can edit `index.html` directly in GitHub or on a computer. Commit changes to the `main` branch; GitHub Pages will redeploy.

## Health note
This app is a habit organizer, not a medical device or a treatment for inflammation. The routines are general wellness suggestions and can be adapted to personal needs.
