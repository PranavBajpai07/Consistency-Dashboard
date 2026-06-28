# FAANG Consistency Dashboard

A personalized daily dashboard for tracking fitness, diet, study, FAANG interview preparation, and interview progress.

Built for a 28-year-old Indian man living in Maharashtra, rooted in Lucknow, motivated by football discipline, and focused on becoming FAANG-ready through consistent daily execution.

## Overview

This dashboard helps track the habits and preparation areas that matter most:

- Workout consistency
- Alternate-day running and abs
- Push-pull-legs strength training
- Diet, protein, water, and calories
- Study time and topics
- Abdul Bari algorithm playlist progress
- William Fiset DSA playlist progress
- Interview preparation
- DSA practice
- Daily LeetCode question
- Applications and networking
- Mock interviews and behavioral preparation
- Interview pipeline progress
- Daily reflections, energy, sleep, and mood

The goal is simple: make daily progress visible, measurable, and motivating.

## Features

- Daily consistency score
- Current streak tracking
- Weekly progress chart
- 30-day analytics and consistency heatmap
- Adjustable daily targets
- Workout, diet, study, and interview prep cards
- Auto-suggested daily training plan for Run/Abs and Push/Pull/Legs
- Daily Abdul Bari and William Fiset video checkboxes
- Daily LeetCode question tracking
- FAANG-focused interview pipeline
- Add, edit, advance, and delete interview entries
- FAANG preparation roadmap
- DSA topic tracker
- Calendar reminder export as `.ics`
- Dark mode
- Daily reflection prompts
- Local browser storage
- JSON export and import for backups
- GitHub Pages and PWA-ready companion files
- Responsive UI for desktop and mobile

## How To Use

Open `index.html` in your browser:

```text
outputs/consistency-dashboard/index.html
```

Then log your daily progress across workout, diet, study, and interview preparation.

Your data is saved automatically in your browser using `localStorage`.

## Files

- `index.html` - the full dashboard app
- `README.md` - project documentation
- `manifest.json` - installable web app metadata
- `service-worker.js` - offline cache support when hosted over HTTPS
- `icon.svg` - app icon

## Backup And Restore

Use the dashboard buttons:

- `Export` downloads your saved dashboard data as JSON.
- `Import` restores a previous JSON backup.
- `Clear` removes all locally saved dashboard data.

Because this app stores data locally in the browser, exporting backups regularly is recommended.

## Routine Setup

The dashboard assumes June 28, 2026 is a `Run + Push` day by default.

You can change this inside `Daily Targets`:

- `Run anchor` controls which date starts the alternate run/abs cycle.
- `PPL anchor` controls which date starts the push-pull-legs cycle.
- `Anchor PPL` controls whether that anchor date is Push, Pull, or Legs.

This lets the app auto-suggest the correct training plan for any selected date.

## Tech Stack

- HTML
- CSS
- JavaScript
- Browser `localStorage`
- Web app manifest
- Service worker

No backend, database, install step, or account is required.

## GitHub Pages Deployment

To publish the dashboard:

1. Upload the files in this folder to a GitHub repository.
2. Go to repository `Settings`.
3. Open `Pages`.
4. Select the branch and folder that contain `index.html`.
5. Save and open the generated GitHub Pages URL.

After it is hosted over HTTPS, the browser can use the manifest and service worker for install/offline support.

## Project Motivation

This project is designed around consistent self-improvement:

- Train like a footballer.
- Study like an engineer.
- Prepare like a FAANG candidate.
- Reflect like someone serious about growth.

Small daily reps compound into interview readiness.

## Future Improvements

- Cloud sync
- Optional backend database
- Calendar API integration
- Cloud sync across devices
- More detailed DSA revision scheduling
- Push notifications
