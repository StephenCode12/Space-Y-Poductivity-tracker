# Work Rate

Work Rate is a small, phone-friendly manufacturing productivity timer. It stores everything in your browser, works offline after the first visit, and can be added to a phone home screen.

## What it does

- Start, pause, resume, and finish a work timer
- Keeps correct time after the screen locks or you switch apps
- Calculates units per hour and minutes per unit
- Saves optional session names and notes
- Keeps separate history and summaries for each work category
- Lets you edit or delete entries
- Exports your history as a CSV file for Excel
- Stores data locally—no account or database

## Put it on GitHub Pages (beginner steps)

1. Download and unzip this project.
2. Sign in at [github.com](https://github.com) and click the **+** button, then **New repository**.
3. Name it `work-rate`, choose **Public**, and click **Create repository**.
4. On the repository page, click **uploading an existing file**.
5. Upload the *contents inside* the `work-rate` folder (`index.html`, `app.js`, `styles.css`, and the other files/folders). Do not upload only the outer folder.
6. Click **Commit changes**.
7. Open **Settings → Pages**.
8. Under **Build and deployment**, choose **Deploy from a branch**.
9. Select branch **main**, folder **/(root)**, then click **Save**.
10. Wait a few minutes. GitHub will show your address, usually `https://YOUR-USERNAME.github.io/work-rate/`.

No custom domain is needed.

## Open it like an app on your phone

**iPhone:** Open the GitHub Pages address in Safari → tap **Share** → **Add to Home Screen**.

**Android:** Open the address in Chrome → tap the three-dot menu → **Add to Home screen** or **Install app**.

## Important data note

Entries are saved only in that browser on that device. Clearing browser/site data removes them, and entries do not automatically sync between your phone and computer. Use **History → CSV** periodically to keep a backup.

## Testing on your computer

For a quick look, double-click `index.html`. Most features work immediately. Offline installation needs the app to be served over HTTPS, which GitHub Pages handles automatically.

## Simple file guide

- `index.html` — the app's screen structure
- `styles.css` — colors, spacing, and mobile design
- `app.js` — timer, calculations, saved entries, editing, and export
- `manifest.webmanifest` — home-screen app information
- `sw.js` — offline support
- `icons/` — app icons

## Updating later

Edit a file on GitHub with its pencil button, then commit the change. GitHub Pages republishes automatically. If an old version remains on your phone, fully close and reopen the app while online.

## Privacy

Work Rate sends no productivity data anywhere. All entries stay in the current browser's local storage unless you export the CSV yourself.
