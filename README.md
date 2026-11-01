# Stretch & Gym

Personal stretching, pull-up and workout tracker. Installable web app that works offline.

- Open https://dboandl.github.io/stretch-gym/ in Chrome on Android, then menu → **Add to Home screen** (or **Install app**).
- Data is stored on the phone. If a GitHub repo and token are set in **Sync** (top right), new entries are also copied to that private repo whenever the phone is online.
- No build step: `index.html` (app), `sync.js` (offline-first sync via the GitHub Git Data API), `sw.js` (offline copy).
