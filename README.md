# FIT FOR THE PIT — ROAD NOTES (free PWA)

This is a free, installable Progressive Web App package built from the FFTP Road Notes journal.

## Files
- `index.html` — the journal interface
- `manifest.webmanifest` — app name, icon and install settings
- `sw.js` — offline cache for the app shell
- `icons/` — app icons generated from the supplied FFTP metal wordmark logo; the actual logo is also embedded in the app masthead

## Publish for free with GitHub Pages
1. Create a free GitHub account if you do not already have one.
2. Create a new public repository, for example `fftp-road-notes`.
3. Upload the contents of this folder (not the ZIP itself) to the repository root.
4. In the repository, open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. It will provide an HTTPS address.
7. Open that HTTPS address on your phone.

## Install
- **iPhone:** open the published address in Safari → Share → Add to Home Screen.
- **Android:** open the published address in Chrome → menu → Install app / Add to Home screen.

## Privacy notes
- Journal entries use browser local storage on the user's device.
- The app contains no ChatGPT/OpenAI integration, analytics, advertising trackers or automatic upload of journal content.
- The manual sharing control prepares an email draft addressed to `fftpit@gmail.com`. The user must review and press Send in their own email app.
- Email is not a private local journal store. Once sent, the message is handled by the user's email provider and the recipient's email provider.
- The service worker caches the app files for offline use. It does not upload journal data.

## Important limitations
- This is a free static PWA, not a native App Store / Google Play app.
- Entries are stored per browser/device and do not automatically sync between devices.
- Clearing browser storage can remove entries; users should export backups.
- Email sharing depends on an email app being configured on the device.
