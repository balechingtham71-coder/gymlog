GYMLOG 1.0 — Personal progress tracker

FILES
- index.html: app
- manifest.json: installable PWA metadata
- sw.js: offline cache
- icon-192.png / icon-512.png: app icons

RUN LOCALLY
1. Extract this ZIP.
2. Open the folder in VS Code.
3. Install the "Live Server" extension.
4. Right-click index.html > Open with Live Server.
5. On your iPhone, open the same local-network URL in Safari (phone and PC on same Wi-Fi).
   For reliable installation and offline use, deploy the folder to a static HTTPS host.

PUBLISH FREE (GitHub Pages)
1. Create/sign in to GitHub.
2. Create a new public repository named gymlog.
3. Upload the five app files to the repository root.
4. Repository Settings > Pages > Deploy from branch > main / root > Save.
5. Wait for the published HTTPS URL.
6. Open that URL in Safari on iPhone > Share > Add to Home Screen.

DATA
- Entries are saved in the browser's localStorage on the device.
- Export a JSON backup from the Data tab regularly.
- Import replaces the current dataset; export first if needed.
- Data is not synced between Windows and iPhone automatically.

V1 FEATURES
- Dashboard and body weight trend
- 30-day / 90-day / all-time chart filters
- Strength history by exercise
- Personal best and latest working weight
- Add, edit, delete records
- JSON backup and restore
- PWA install and basic offline caching
