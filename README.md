# 📅 SMM Production Planner

A sleek, modern **Social Media Management Production Planner** built with pure HTML, CSS, and JavaScript — no dependencies required.

![SMM Production Planner](https://effervescent-vacherin-f0de56.netlify.app/)

## ✨ Features

- 📆 **Monthly Calendar View** — Full month grid with task chips per day
- 🗂️ **Task Types** — Shoot, Edit, and Post tasks with color-coded statuses
- 👥 **Team Members** — Sidebar list of videographers/content creators
- 🔍 **Filter by Type** — Quickly toggle between Shoot / Edit / Post views
- ➕ **Add Tasks** — Click any day cell to add a new scheduled task
- 📊 **Live Stats** — Real-time count of tasks by status (Done, Pending, Missed)
- 🗓️ **Mini Calendar** — Sidebar mini calendar for quick navigation
- 💾 **Local Persistence** — Tasks saved to `localStorage` (no backend needed)

## 🚀 Getting Started

This is a zero-dependency, single-file web app. Just open it in any modern browser:

```bash
# Clone the repository
git clone https://github.com/AbdurashidovUz/smm_management.git
cd smm_management

# Open in browser
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Or serve it locally with any static server:

```bash
npx serve .
# or
python -m http.server 8080
```

Then visit `http://localhost:8080` (or `http://localhost:3000` with npx serve).

## 🏗️ Project Structure

```
smm_management/
└── index.html    # Complete app — HTML + CSS + JS in one file
```

## 🎨 Tech Stack

| Layer      | Technology           |
|------------|----------------------|
| Structure  | HTML5 (Semantic)     |
| Styling    | Vanilla CSS (custom properties, grid, flexbox) |
| Logic      | Vanilla JavaScript (ES6+) |
| Fonts      | Google Fonts — DM Sans, Syne |
| Storage    | Browser `localStorage` |

## 📌 Task Statuses

| Status    | Color     | Meaning                        |
|-----------|-----------|--------------------------------|
| 🟠 Shoot  | Orange    | Content recording scheduled    |
| 🟣 Edit   | Purple    | Video/photo editing in progress |
| 🩷 Post   | Pink      | Ready to publish to social     |
| ✅ Done   | Green     | Completed                      |
| 🔴 Missed | Red       | Deadline passed, not done      |
| 🟡 Pending| Yellow    | Upcoming, not started          |

## 🌐 Live Demo

Deployed on Netlify: **[https://effervescent-vacherin-f0de56.netlify.app/](https://effervescent-vacherin-f0de56.netlify.app/)**

## 📄 License

MIT — feel free to fork and adapt for your team's workflow.
