# LifeLog — Personal Health & Life Tracker

A clean, private, single-file web app for tracking your **medical**, **physical**, **job**, and **exercise** details and writing **daily reports**. No accounts, no servers, no install — just open the file in your browser.

![Built as a single HTML file](https://img.shields.io/badge/build-single%20HTML%20file-5b8cff) ![No backend](https://img.shields.io/badge/backend-none-3ecf8e) ![License: MIT](https://img.shields.io/badge/license-MIT-7c5bff)

**▶ Live demo: [umerniazi96.github.io/lifelog](https://umerniazi96.github.io/lifelog/)**

![LifeLog dashboard](screenshot.png)

*(Screenshot shows sample data — the app starts empty and stores everything locally in your browser.)*

## ✨ Features

- **Dashboard** — at-a-glance stats: report streak, weekly workouts & active minutes, current weight + BMI, average energy.
- **Daily Report** — mood, energy & pain scales, sleep, water, weight, and a free-form journal entry.
- **Exercise log** — workouts by type, duration, intensity, calories, and notes, with weekly volume totals.
- **Medical** — blood type, allergies, conditions, medications, physician, emergency contact, insurance.
- **Physical** — height, weight, target, vitals, with auto-calculated age, BMI, and distance to goal.
- **Job** — title, employer, schedule, hours, stress level.
- **History** — a unified timeline of everything you've logged.
- **🖨 Printable medical card** — generate a clean one-page summary; "Save as PDF" for doctor visits.
- **Backup & restore** — export/import your data as a JSON file.

## 🔒 Privacy

All data is stored **only in your browser** via `localStorage`, on your own device. Nothing is ever uploaded or transmitted. The published app file contains **no personal data** — your entries never leave your machine.

> ⚠️ Because data lives in browser storage, clearing your browser's site data will erase it. **Export a backup regularly.**

## 🚀 Usage

1. Download [`index.html`](index.html).
2. Double-click to open it in any modern browser.
3. Start logging. That's it.

To use it across devices, export a backup on one device and import it on another.

## 🌐 Hosting a public link (optional)

Since it's a static file, you can host it free anywhere:

- **Netlify Drop** — drag `index.html` onto <https://app.netlify.com/drop>.
- **GitHub Pages** — enable Pages on this repo (Settings → Pages → deploy from `main`).
- **Cloudflare Pages / Vercel** — point at this repo.

## ⚕️ Disclaimer

This is a personal organization tool, **not medical advice or a medical device**. Always verify health information with a qualified professional.

## License

[MIT](LICENSE) — free to use, modify, and share.
