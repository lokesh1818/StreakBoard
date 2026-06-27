# 📚 DSA Daily

A simple, offline-first study schedule tracker built as a single HTML file — no install, no login, no server needed.

---

## What it does

DSA Daily gives you a calendar view of your entire study month. Click any date to see that day's schedule, check off tasks as you complete them, and watch your streak grow.

---

## Daily Schedule

| Time | Block |
|---|---|
| 8:00 – 9:00 AM | Wake up & solve 1 DSA problem |
| 9:00 – 10:00 AM | Break — eat & relax |
| 11:00 AM – 3:00 PM | Read & study core concepts |
| 3:00 – 5:00 PM | Afternoon break |
| 5:00 – 8:00 PM | Learn new concepts / topics |
| 9:00 PM – 12:00 AM | DSA practice session |

---

## Features

- **Calendar view** — browse any month, past or future
- **Daily task panel** — click a date to expand its full schedule
- **Checkboxes** — tick off each task as you complete it
- **Progress bar** — see how far along you are each day
- **Streak counter** — tracks consecutive days where all tasks are completed
- **Color-coded badges** — instantly see what type of block each task is
- **Progress dots** — each calendar cell shows mini dots for task completion at a glance
- **Dark mode** — automatically follows your system preference
- **Offline & private** — everything saved locally in your browser, no data sent anywhere

---

## How to use

### Option 1 — Open locally
Download `dsa-study-schedule.html` and double-click it to open in any browser. That's it.

### Option 2 — Get a free link (share / bookmark)
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag and drop `dsa-study-schedule.html` onto the page
3. You'll get a free public URL in seconds — no account needed

### Option 3 — Use on your phone
Send the file to yourself via WhatsApp or email, open it in your mobile browser (Chrome / Safari), and add it to your home screen for quick access.

---

## Data & privacy

All your progress is saved in your browser's `localStorage`. Nothing is sent to any server. If you clear your browser data, your progress will be reset — so avoid clearing site data for the file if you want to keep your streak.

---

## Tech stack

Pure HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies, no build step. One file, runs anywhere.

---

## Customizing

Want to change the schedule? Open the HTML file in any text editor and find the `TASKS` array near the bottom:

```js
const TASKS = [
  { id: 't1', label: 'Wake up & solve 1 DSA problem', time: '8:00 – 9:00 AM', badge: 'badge-morning' },
  // add, remove, or edit tasks here
];
```

Each task has:
- `id` — unique identifier (keep these unique)
- `label` — what shows in the task list
- `time` — the time range shown as a badge
- `badge` — color style (`badge-morning`, `badge-study`, `badge-break`, `badge-evening`, `badge-night`)

---

## License

Free to use and modify for personal use.
