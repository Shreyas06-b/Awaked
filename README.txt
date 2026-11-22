AWAKED 4.4 — SLEEPING FOX EDITION

This package updates the Awaked PWA with the approved sleeping fox identity,
a first-run welcome guide, weekly sleep comparison, clearer visual feedback,
and a versioned offline cache. Existing Firebase Authentication, Firestore
sync, journal entries, saved routines, profile and local storage key are retained.

FILES
- index.html
- manifest.json
- sw.js
- icon.svg
- icon-192.png
- icon-512.png

DEPLOY
1. Back up the current GitHub repository before replacing anything.
2. Upload all six files to the repository root, preserving the filenames.
3. Commit to the main branch and wait for GitHub Pages to finish deploying.
4. Open the site in Chrome and allow the new service worker to update.
5. If the installed app still shows the old icon, remove the old home-screen
   shortcut and install Awaked again from the deployed site.

NOTES
- This package does not intentionally clear localStorage or Firebase data.
- Weekly comparison uses only manually entered journal records.
- Reminders are browser-scheduled and may not fire after the browser/app closes.
- Google sign-in still requires the deployed domain to be listed in Firebase
  Authentication > Settings > Authorized domains.
- Test sign-in, sync, export, delete-account, and offline loading after deployment.
