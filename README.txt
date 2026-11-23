AWAKED 4.6 — EXPERIENCE UPDATE

Files to deploy in the ROOT of the existing GitHub Pages repository:
- index.html
- manifest.json
- sw.js
- icon.svg
- icon-192.png
- icon-512.png

This update is built from the existing Awaked 4.5.3 source. It preserves the existing Firebase project, Firestore document path (users/{uid}/appData/main), localStorage key (awaked2-data), journal and saved schedule structures.

Highlights:
- First-time welcome, Google/guest choice and guest profile setup
- Returning-user onboarding guard
- Minimal hybrid home dashboard
- Unified bedtime-first / fixed-wake-up calculator with full time intervals and durations
- Sleep fingerprint, sleep-goal shortfall estimate and weekly summary
- App-wide formatted clock and displayed time preference

Deployment:
1. Back up your current repository files first.
2. Upload all six files to the repository ROOT and replace existing files.
3. Commit to main and wait for GitHub Pages deployment to succeed.
4. Open the site in Chrome and verify onboarding, calculator, journal, settings and sync.

Important:
- Existing journal and routine data is not intentionally cleared or migrated to a new storage key.
- Guest data remains local until the user signs in. Signing in merges local entries and schedules with the user's cloud document.
- Browser-native time picker appearance may still follow Android/browser locale; formatted app text and live clock follow the Awaked 12/24-hour preference.
- Reminder delivery limitations are unchanged.
- This package has passed static JavaScript syntax and DOM ID-reference checks. Live Firebase authentication and sync have not been tested in this environment.
