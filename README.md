# Medicine Reminder

A simple web app to track daily medicine schedules with browser notifications.

## Features

- Add medicines with name, dosage, and scheduled time
- Mark medicines as taken (resets daily at midnight)
- Browser notifications when it's time to take a medicine
- Data stored locally in your browser (nothing sent to a server)

## Setup

No build step required — it's a single HTML file.

### Run locally

Open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

### Deploy

Hosted via GitHub Pages from the repository root.
