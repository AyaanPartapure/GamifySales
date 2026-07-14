# DealerVerse — Gamified Dealership Management Platform (Frontend Demo)

Vanilla HTML/CSS/JS, no frameworks, no build step. Open `index.html` in a browser.

## Structure
- `index.html` — marketing landing page
- `pages/` — 14 app screens (login, dashboard, booking journey, leaderboard,
  profile, rewards, achievements, department dashboards, sales competition,
  booking details, notifications, admin panel, analytics, settings)
- `css/tokens.css` — design tokens (color, type, radius, shadow)
- `css/components.css` — shell layout + full component library
- `js/shell.js` — renders the sidebar/topbar shared by every app page
- `js/data.js` — placeholder data (employees, bookings, leaderboard…)
- `js/fx.js` — particles, count-up numbers, confetti, toasts, flying XP, tilt cards
- `assets/` — reserved for real imagery; demo uses inline SVG/emoji

## Design system: "Ignition"
Idle blue → mid violet → redline gold gradient used across progress bars,
buttons and the signature race-track booking journey. Space Grotesk for
display type, Inter for body, JetBrains Mono for data/XP/VIN-style figures.

## Notes
All data is placeholder/mock. Every internal page is reachable from the
sidebar, so the whole flow (landing → login → dashboard → every module) is
click-through demoable end to end.
