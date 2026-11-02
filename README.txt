REALM — first playable MVP

Files:
- index.html: the app
- manifest.webmanifest: installable PWA metadata
- sw.js: offline app-shell cache

Run locally:
Open index.html in a browser to test the app. Installability and offline caching require HTTPS or localhost.

Free hosting (GitHub Pages):
1. Create a free GitHub account and a new public repository named realm.
2. Upload index.html, manifest.webmanifest and sw.js to the repository root.
3. Open repository Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for the Pages URL to appear. Open it in Chrome on Android.
6. Chrome menu (⋮) > Install app / Add to Home screen.

Data:
Progress saves in this browser's localStorage. It is not synced across devices. Use Records > Export backup regularly. Import backup restores it.

Notes:
This is an early MVP. Quest recurrence is currently managed manually: when a daily/weekly quest is completed, add it again for its next cycle. Rank thresholds are level-based in this first version and will be expanded later.
