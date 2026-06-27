# mashQ

A hyper-focused, ultra-minimalist push-up tracker. Log your daily push-ups as separate
"deposits" throughout the day and review your progress over time.

Single-file web app — all HTML, CSS, and JavaScript live in [`index.html`](index.html).
No build step, no dependencies, works fully offline. Data is stored locally in the
browser via `localStorage`.

## Features

- **Daily Bank** — a running total of today's push-ups, front and center.
- **Deposit logging** — type a number, hit *Log Set*; the input resets instantly so every
  effort is a separate, timestamped entry.
- **New Day / Reset** — archive the current count and start fresh, or clear a mistyped input.
  The bank also auto-rolls over at midnight.
- **Reports** — Day view (timestamped sets), Month view (per-day totals, tap to drill in),
  and a date/month picker to jump to any point in history.
- **Dark mode** — toggle in the top-right corner; your choice is remembered.

## Running it

Open `index.html` in any browser. On iPhone, open it in Safari and choose
**Share → Add to Home Screen** for a full-screen, app-like experience.

## Roadmap

- Wrap with [Capacitor](https://capacitorjs.com/) for a native iOS build distributable
  via TestFlight.
