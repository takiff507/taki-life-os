# Taki Life OS

Offline personal dashboard for tasks, habits, focus, notes, simple expenses, and JSON backups.

## Live Demo

After GitHub Pages is enabled:

https://takiff507.github.io/taki-life-os/

## Features

- Dashboard metrics for tasks, habits, focus, and monthly spending
- Kanban task board with priority and due dates
- Habit tracker with seven-day history and streaks
- Pomodoro-style focus timer with session logs
- Local notes with search
- Expense tracker with category bars
- Dark and light theme
- Export/import backup as JSON
- Works without an API, login, database, or build step

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- `localStorage` for offline persistence

## Run Locally

Open `index.html` directly in a browser, or run a static server:

```bash
python -m http.server 4173
```

Then visit:

```text
http://localhost:4173
```

## Data

All app data is stored in the user's browser through `localStorage`. Use the Data tab to export a JSON backup before clearing browser storage or switching devices.

## License

MIT
