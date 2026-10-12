# Day Designer

A planner for your day. Lock any block at a set time and everything else reflows around it.

## Put it online (GitHub Pages)

1. On github.com, create a new **public** repo named `day-designer`.
2. Choose **Add file → Upload files** and drag in everything from this folder: `index.html`, `manifest.webmanifest`, `sw.js`, and the `icons` and `fonts` folders. Commit.
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, pick `main` and `/ (root)`, then Save.
4. After a minute or two the app is live at `https://<your-username>.github.io/day-designer/`.

## Put it on your Home Screen (iPhone)

1. Open that link in **Safari**.
2. Tap **Share → Add to Home Screen**, then tap **Add**.
3. Open it from the new icon. It runs full screen and works offline.

## Notes

- Your plan is saved on the phone, inside the Home Screen app. The Safari tab keeps its own separate copy.
- To ship an update, upload the new `index.html` and change `CACHE` in `sw.js` (for example `v1` → `v2`). The update shows up the second time you open the app.
