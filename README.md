# High Mileage Hybrid 1.1 — Pilot App

Mobile-first, installable static web app built from the High Mileage Hybrid 1.1 Auto Progression workbook.

## Features
- Full 8-week, 5-day program from the workbook
- High Mileage branding and app icon
- Workout logging: load, reps/time, RIR, notes, completion
- Strength/BUILD auto-progression suggestions based on prior-week performance
- Rest timer
- Exercise guide
- Weekly completion dashboard
- Pilot feedback ratings and notes
- JSON and CSV export for pilot review
- Offline/PWA support after first load
- All pilot data stored locally on the athlete's device

## GitHub Pages deployment
1. Create a new GitHub repository (example: `high-mileage-hybrid-pilot`).
2. Open this ZIP and upload the **contents** of the `high-mileage-hybrid-app` folder to the repository root. Do not upload the ZIP itself.
3. Commit the files to `main`.
4. Go to Settings → Pages.
5. Under Build and deployment choose **Deploy from a branch**.
6. Select `main` and `/ (root)`, then Save.
7. After GitHub publishes it, open the Pages URL on the phone.
8. iPhone: Safari → Share → **Add to Home Screen**. Android/Chrome: menu → **Install app** / Add to Home screen.

## Pilot use
Have the athlete enter loads, actual reps/time, RIR, and notes after each movement. Week 2+ strength and BUILD movements calculate a suggested next load when prior-week data exists. The Progress tab can export all training logs as CSV and all pilot data/feedback as JSON.

## Important
Browser storage is device-specific. Export pilot data before clearing browser data or changing devices.
