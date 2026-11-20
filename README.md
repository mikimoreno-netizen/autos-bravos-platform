# Autos Bravos Platform

## Photo Guide (pilot)
Mobile vehicle photography app: [source](docs/photo-guide/index.html).

### Publish on GitHub Pages
Open **Settings → Pages** in this repository. Under **Build and deployment**, choose **Deploy from a branch**, select **main**, folder **/docs**, then save.

Once deployment completes, the app URL will be:

https://mikimoreno-netizen.github.io/autos-bravos-platform/photo-guide/

### Important safety limitations
- Pilot only: data and photographs are stored **locally in the user's browser (IndexedDB)** and are **not** uploaded to GitHub or to central storage.
- Export the ZIP frequently, and transfer it to approved dealership storage; browser storage can be lost.
- The GitHub Pages site is **public** and has no staff login. Do not input customer personal information.
- Camera access requires HTTPS and permission in mobile Safari/Chrome.
- Physical camera distance and angle are **not automatically measured**. The visible guide is manual.
- Real-device camera and IndexedDB testing are required before actual dealership use.

The published version is a **self-contained single HTML file**, with no third-party services or API keys.
