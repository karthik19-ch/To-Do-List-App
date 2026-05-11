# TASKR — Interactive To-Do List App

A sleek, production-grade To-Do List app built with **vanilla HTML, CSS, and JavaScript** — no frameworks, no dependencies.

---

## Features

| Feature | Details |
|---|---|
| ✅ Add Tasks | Type + press Enter or click `+ ADD` |
| 🗑️ Delete Tasks | Click the × button on any task |
| ☑️ Mark Completed | Click the circle checkbox or task text |
| 🏷️ Priority Tags | LOW / MID / HIGH labels per task |
| 💾 Local Storage | Tasks persist across browser sessions |
| 📊 Progress Bar | Live progress tracking (% done) |
| 🔍 Filters | View ALL / ACTIVE / DONE tasks |
| 🧹 Clear Done | Remove all completed tasks in one click |
| 📱 Responsive | Works on mobile, tablet, and desktop |
| 🎨 Animations | Smooth slide-in/slide-out transitions |
| 🔔 Toast Alerts | Contextual feedback messages |

---

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, animations, responsive grid

---

## How to Run

1. Open `index.html` directly in any modern browser — no server needed.
2. Or host it on GitHub Pages, Netlify, or any static host.

---

## File Structure

```
todo-app/
├── index.html   ← Everything (HTML + CSS + JS in one file)
└── README.md    ← This document
```

---

## Local Storage

All tasks are saved under the key `taskr_tasks` in `localStorage` as a JSON array:

```json
[
  {
    "id": 1716390000000,
    "text": "Ship the feature",
    "done": false,
    "priority": "high",
    "createdAt": "2025-05-11T10:00:00.000Z"
  }
]
```

Data persists across browser refreshes and sessions automatically.

---

## Design Aesthetic

- Dark industrial theme with electric yellow (`#e8f84b`) and crimson (`#f84b6e`) accents
- **Bebas Neue** for headings, **DM Sans** for body, **JetBrains Mono** for stats/meta
- Hover micro-interactions and animated task entry/exit
- Priority color coding: 🔴 HIGH · 🟡 MID · 🔵 LOW

---

## 🚀 Live Demo

🔗 Live Website:
https://karthik19-ch.github.io/Portfolio_Website/

---

## 📂 GitHub Repository

🔗 Source Code:
https://github.com/karthik19-ch/portfolio-website
