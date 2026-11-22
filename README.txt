AWAKED 2.0 — GitHub Pages update

WHAT'S NEW:
- Four-tab navigation: Home, Journal, Saved, Profile.
- Animated splash screen.
- Normal and reverse sleep calculator.
- Share calculated plan (native share sheet where supported; clipboard fallback).
- Journal with manually entered actual sleep, notes, ratings, weekly average and chart.
- Saved schedules with categories including College, Weekend, Exams, Work and Custom.
- Local profile with name, photo, date of birth and optional phone.
- Dark/light theme, export data and clear local data.
- Offline PWA cache.

HOW TO UPDATE YOUR EXISTING GITHUB PAGES APP:
1. Extract this ZIP.
2. Open your existing GitHub repository named awaked.
3. Open the repository root (main branch).
4. Choose Add file > Upload files.
5. Upload and commit index.html, manifest.json, sw.js and icon.svg from this package, replacing the existing versions.
6. Wait for GitHub Pages to redeploy, then open your existing app URL.
7. If the old version remains, close the installed app and refresh the website. Service worker cache is versioned awaked-v2; if needed clear Chrome site data for the Pages site and reopen.

IMPORTANT LIMITATIONS:
- This GitHub Pages version has no real sign-in, cloud sync or multi-device profile. Profile, journal and schedules are stored locally in the browser on each device.
- Sleep journal entries are manual; the app does not detect sleep or measure sleep quality.
- Phone number is optional and is not sent anywhere.
- Data is stored in this browser's localStorage. Export your data from Profile before clearing browser data or switching devices.
- Profile photos are resized before local storage. If local storage is full, choose a smaller photo.
- Sleep calculations use elapsed clock time and assume same local timezone; no alarm is set by this web app.
