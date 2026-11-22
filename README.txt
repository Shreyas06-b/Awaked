AWAKED 4.5.1 — JOURNAL, SLEEP BAR & SYNC REPAIR

This release restores missing week-on-week comparison elements used by the journal renderer, which could stop journal rendering with a JavaScript error. It also retries cloud saves safely when another save is in progress and retains the personal sleep-goal setting in Firestore sync.

Publish:
1. Back up your repository.
2. Extract this ZIP and upload all six app files to the repository root, replacing matching files.
3. Commit to main and wait for GitHub Pages deployment.
4. Reload Awaked and test journal entries, the sleep-goal progress bar, and cloud sync while signed in.

The local storage key and Firestore document path are unchanged. This package does not intentionally clear local or cloud data.
