DRAGONKNIGHT WEEKLY TRACKER — INSTALLABLE WEB APP

WHAT'S INCLUDED
- index.html: the tracker app
- manifest.webmanifest: home-screen app name, icon, and standalone display settings
- sw.js: caches the app so it can open offline after the first successful load
- icons/: home-screen icons

IMPORTANT
A local HTML file or ZIP cannot by itself install a proper PWA. For the install prompt and offline cache to work, host these files on an HTTPS website. This package is ready to publish as a static website, for example with GitHub Pages.

ANDROID INSTALL
1. Publish the contents of this folder to an HTTPS static website.
2. Open that website's URL in Chrome on your Android tablet.
3. Open Chrome's ⋮ menu and choose "Install app" or "Add to Home screen" (wording varies).
4. Confirm. The tracker should appear as an icon and open in its own app-style window.

DATA NOTE
The tracker saves entries in browser local storage on that device/browser. Export JSON backups regularly. Reinstalling, clearing browser storage, or opening it in a different browser may not carry entries over; restore from a JSON backup when needed.

To share the APP, share the hosted website URL or this source package. To share the DATA, export a JSON backup from inside the tracker.
