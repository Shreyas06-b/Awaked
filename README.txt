AWAKED 4.5.2 - JOURNAL DATE FIX

This update fixes today's journal entry being excluded from the 7-day totals when the app is opened before 12:00 PM. The entry date was being interpreted as noon, then compared against the current morning time.

Upload/replace these files in the ROOT of the GitHub repository on the main branch:
- index.html
- sw.js

Keep manifest.json and icon files as they are. Do not delete app data or Firestore records.
After GitHub Pages deployment succeeds, open the site in Chrome and reload. The new service-worker cache name triggers the updated files.
