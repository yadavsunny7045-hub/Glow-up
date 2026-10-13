# GlowUp Quest

A responsive installable web app (PWA) for daily tasks, XP, vegetarian meal ideas, home dumbbell workouts, weight tracking, settings and local backup/restore.

## Easiest Android install (recommended)
A PWA install and offline service worker require a secure HTTPS site (or localhost). Opening `index.html` directly from a file manager is only a preview and may not enable installation/offline support.

### Publish with GitHub Pages
1. Extract this ZIP on a computer, or upload the five files from the `glowup_quest` folder.
2. Create a GitHub repository named `glowup-quest` and upload `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, and optionally `README.md` to its root.
3. Open repository **Settings → Pages**. Choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. Wait for the published `https://YOUR-USERNAME.github.io/glowup-quest/` link.
5. Open that link in Chrome on Android. Tap **⋮ → Install app** or **Add to Home screen** and confirm.

## Features
- Daily checkbox missions and XP; task XP is awarded once per task per day.
- Vegetarian Indian meal schedule with estimated calories/protein.
- Home dumbbell/bodyweight routine and Tuesday recovery.
- Weight logs and simple trend chart.
- Editable calorie, protein, water and weight targets.
- JSON export/import and clear-data controls.
- Optional browser notification permission/test; exact scheduled notifications aren't guaranteed while the browser is closed.
- Service-worker cache for offline shell after first visit on HTTPS.

## Data and health notes
Progress is stored in browser localStorage on this device. Export a backup before clearing browser data or changing browsers/devices. Nutrition values are estimates, not medical advice. Gaining 12 kg in one month is not a safe or realistic muscle-gain target; consider a clinician/dietitian for a personalized plan.

This package is a web app/PWA, not a signed native Android APK and not published to Google Play.
