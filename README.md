# Field Strength

A free, installable, phone-first workout tracker for a 12-week progressive barbell program.

**App URL once GitHub Pages is enabled:** https://garrettmasters.github.io/field-strength/

## Features

- **Today:** Today's workout, week overview, and a weight check-in.
- **Plan:** The 12-week REP-rack barbell program. Three full-body sessions weekly for weeks 1–4; four upper/lower sessions weekly for weeks 5–12.
- **Exercise references:** Each exercise has a position sketch, technique cues, safety notes, and a link to find a demonstration video.
- **Workout logging:** Track sets, reps, and total barbell weight. The app remembers unfinished sessions on your device.
- **Adaptive recommendations:** Propose a 5–10 lb increment after completing all sets at the top of the rep range, or a small reduction after struggling with the minimum. Always use sound technique and judgment.
- **Body-weight progress:** Graph weight and compare recent weekly averages. Current body weight, start, goal, and loads display pounds first, kilograms second.
- **Reminders:** Export 12 weeks of events with 15-minute reminders to import into Apple Calendar.
- **Offline:** A service worker caches the app after the first load. External video links require an internet connection.
- **Privacy:** No login, analytics, tracker, server, or subscription. Logs are stored locally in your browser. Export backups regularly from Settings.

## GitHub Pages

The repository includes a GitHub Actions workflow in the .github/workflows/pages.yml file, triggered on pushes to the main branch.

Go to **Settings → Pages → Build and deployment → Source → GitHub Actions**, if that source is not already selected. Check **Actions** for a successful deployment.

On iPhone, open the live HTTPS URL in **Safari → Share → Add to Home Screen**. If asked, choose Open as Web App.

## Usage

Go to **Settings** and choose the Monday for your first training week. You can start a workout directly from Plan even before your official start date. Log load as the **total weight on the bar in lb**, not plates alone.

The exercise illustrations are simplified guides, not substitutes for demonstration or coaching. Start with light weights and use rack safeties when lifting alone.

## Important limitations

- Static PWA, so **no native background push notifications**. Use calendar reminders.
- User data lives on your device and this site's URL. It does not sync automatically.
- Adaptive suggestions use simple rules, not AI coaching or medical advice.
- The first beta uses a scalable SVG app icon.

## Technology

Vanilla HTML, CSS, JavaScript, PWA manifest and service worker. No build tools, dependencies, or API keys.
