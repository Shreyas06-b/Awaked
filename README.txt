AWAKED 3.0 — GitHub Pages + Firebase

FILES
- index.html
- manifest.json
- sw.js
- icon.svg
- README.txt

DEPLOY
1. Open your existing repository: https://github.com/Shreyas06-b/Awaked
2. Upload these five extracted files to the repository root, replacing the existing files.
3. Commit the changes and wait for GitHub Pages to deploy.
4. Open https://shreyas06-b.github.io/Awaked/

FIREBASE FEATURES
- Optional Google sign-in; guest mode remains available.
- Guest journal entries and saved schedules are merged with the cloud copy on first sign-in.
- Signed-in data is stored at users/{uid}/appData/main.
- The published Firestore rules should restrict access to the matching authenticated UID.
- Profile name, optional DOB/phone, schedules, journal and preferences sync. Profile photo stays local for now.

IMPORTANT
- Firebase web config is client-side configuration, not a service-account key. Never publish service-account private keys.
- Do not delete the repository. Replace the existing five files in the repository root.
- Firestore security depends on rules, not secrecy of the web config.
