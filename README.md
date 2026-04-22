# Chronicle — Personal Life Archive PWA

## Install on iPhone (Safari)

1. Open `index.html` in Safari on your iPhone
2. Tap the **Share** button (rectangle with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Name it **Chronicle** and tap **Add**
5. The app icon will appear on your home screen like a native app

## Features

- **Today Timeline** — Add tasks with times, swipe/tap to complete with animations
- **Progress Bar** — See daily completion at a glance
- **Streak Counter** — Stay motivated with consecutive day tracking
- **Archive** — Full history of everything you've ever completed, searchable by day/week/month/year/all time
- **Future Self** — Write promises to yourself and track their status
- **Habits** — Daily habit tracker with 7-day visualization
- **Daily Reflection** — Mood + notes logged per day
- **Quick AI Parse** — Type naturally: "gym tomorrow 7pm" → auto-fills form
- **Offline Support** — Works without internet (via Service Worker)

## Data Storage

All data is stored in your browser's localStorage — 100% private, on-device.

## File Structure

```
chronicle-app/
├── index.html      ← Main app (open this in Safari)
├── manifest.json   ← PWA manifest for home screen install
├── sw.js           ← Service worker for offline support
└── README.md       ← This file
```

## Host It (optional, for full PWA)

For the full PWA experience with offline support, host these files on any static server:
- GitHub Pages (free)
- Netlify (free)
- Vercel (free)

Just drag the folder into Netlify and you'll get a URL you can open in Safari.
