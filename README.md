# 🗓️ Habit Tracker

I created a clean, distraction-free habit tracker that lives entirely in your browser. No accounts, no subscriptions, no fluff — just you and your habits.

Built as a single HTML file, so you can open it locally, host it anywhere, or drop it into a repo and call it done.

------

## What it does

- Track any habits you want across a full monthly calendar grid
- Check off each day as you go — future dates stay locked
- See your daily progress (Done / Not Done / %) right below the grid
- Watch a monthly completion chart build itself as the month progresses
- Add, edit, or delete habits anytime without losing old data

Everything saves automatically to your browser's `localStorage` — no server, no database, no sign-in required.

------

## Getting started

No install needed. Just open the file.

```bash
git clone https://github.com/KartikeySahay/habit-track.git
cd habit-tracker
open habit-tracker.html   # or just double-click it
```

That's it.

-----

## Tech stack

| Thing | What it's doing |
|---|---|
| Vanilla HTML/CSS/JS | Everything — no framework needed |
| Chart.js | Monthly progress area chart |
| DM Sans + DM Mono | Typography (via Google Fonts) |
| localStorage | Persisting your data in the browser |

-----

## Limitations worth knowing

Since data lives in `localStorage`, it's tied to the browser and device you're using. Clearing your browser data will wipe it. If you want cross-device sync or user accounts, you'd need to wire up a backend — the data model is simple enough to make that straightforward.

-----

## License

MIT — do whatever you want with it.
