AWAKED — FINAL CREATOR CREDIT UPDATE

This update preserves the existing Awaked app and its current features. It does not add new sleep features or remove existing functionality.

What changed:
- Made the existing developer credit on the Home screen more visible with a card-style treatment.
- Updated the About label from Awaked 3.0 to Awaked 4.0.
- Removed a duplicate export button ID so the data export action has one clear entry point.
- Included bedtime and wake-up reminder preferences in Firestore sync.
- Updated the service-worker cache version and activation handling so the latest app files replace older cached files.
- Corrected a stray escaped newline in the JavaScript that prevented the uploaded index.html from parsing.

PUBLISH:
1. Extract this ZIP.
2. Open the AWAKED GitHub repository.
3. Upload the five files inside the extracted folder directly into the repository root (not the folder itself), replacing the existing files: index.html, manifest.json, sw.js, icon.svg, README.txt.
4. Commit the changes and wait for GitHub Pages to deploy.
5. On your device, open Awaked and perform a hard refresh. If the old version remains on Android, close the installed PWA/browser tab fully and reopen it.

Existing calculator, Journal, Saved schedules, Profile, Google sign-in, Firestore sync, and all existing screens/features are retained.
