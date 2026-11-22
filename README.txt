AWAKED 4.0 — Account, recommendations, consistency and reminders

DEPLOY: Extract this ZIP and upload all five files to the root of the existing GitHub repository https://github.com/Shreyas06-b/Awaked, replacing previous versions. Commit changes and wait for GitHub Pages.

FEATURES
- 14-day sleep consistency estimate based on bedtime and wake-time variation; requires at least 3 journal entries. Not a medical or sleep-quality score.
- Smart recommendation based on recent journal history, suggesting a regular wake time and approximate bedtime.
- Optional bedtime and wake-up browser notifications. Scheduled while the app is open; browser timers may not run if the app/browser is closed. Reliable closed-app delivery requires push notification infrastructure.
- JSON export includes local data and a cloud copy when signed in.
- Account deletion reauthenticates with Google and deletes users/{uid}/appData/main, users/{uid} and the Firebase Authentication user. Extend deletion logic if more cloud collections are added later.

Existing Google login, guest mode, Firestore sync, calculator, journal and saved routines are retained.
