# Stillwater — Christian Spiritual Web App

A responsive, animated Christian spiritual landing page with a sunrise-and-cross visual, numbered square menu cards, scripture reflections, and a modal for each spiritual tool. Notes are saved locally in the visitor's browser.

## Deploy to Cloudflare Pages

### Option A — Upload the ZIP
1. Extract this ZIP on your computer.
2. Open the Cloudflare dashboard and go to **Workers & Pages → Create → Pages → Upload assets** (wording may vary).
3. Upload the extracted project files/folder. The root must contain `index.html`.
4. Deploy.

### Option B — GitHub
1. Create a new GitHub repository.
2. Upload **the contents** of this folder (not the ZIP itself) to the repository root.
3. In Cloudflare, open **Workers & Pages → Create → Pages → Connect to Git**.
4. Select the repository. Use **no build command** and set the build output directory to `/` (root).
5. Save and deploy.

## Customize
- Main design and content: `index.html`
- Background artwork: `assets/sunrise-cross.jpg`
- App install metadata: `manifest.webmanifest`
- Offline caching: `sw.js`

## Notes
- Google Fonts are loaded online; system fallback fonts are included.
- Reflection notes are stored in local browser storage and are not synced between devices.
- This is a static front-end app; it does not include user accounts or cloud database.
