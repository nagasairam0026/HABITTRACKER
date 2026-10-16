# ⚡ HabitFlow — Modern Habit Tracker & Daily Routine Planner

[![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)](https://github.com/nagasairam0026/HABITTRACKER)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success.svg)](https://github.com/nagasairam0026/HABITTRACKER)

> **"Small steps. Strong habits."**  
> HabitFlow is a lightweight, responsive, and feature-rich habit tracking web application designed to help you build consistency, track daily tasks, and achieve your goals with zero external dependencies.

---

## ✨ Key Features

### 🌟 Habit Tracking & Routines
- **Daily Habits & Check-ins:** Easily complete habits with satisfying visual and audio feedback.
- **7-Day Mini Heatmap Dots:** Each habit card displays a 7-day mini dot history (`M T W T F S S`) right on the card for quick momentum checks.
- **Current & Best Streaks:** Automatically tracks both continuous daily streaks and all-time record streaks (`🔥`).
- **Target Goals & Frequency:** Set custom goals (e.g., *8 glasses*, *20 pages*, *30 mins*) and frequencies (Daily, Weekdays, Weekends).
- **Categories & Tags:** Organize your habits into categories like **🏃 Health & Fitness**, **💼 Productivity**, **🧘 Mindfulness**, **📚 Learning**, and **🌱 Personal**.
- **Live Search & Smart Sorting:** Instant search and sort habits by *Highest Streak*, *Pending First*, or *Alphabetical*.

### 📊 Deep Insights & Visuals
- **Habit Insights Modal:** Click 📊 on any habit to inspect current streak, all-time record streak, total lifetime completions, monthly success rate, and a 30-day activity heatmap.
- **Interactive 7-Day Momentum Chart:** Responsive HTML5 Canvas chart displaying completion counts across the week.
- **Consistency Calendar:** Visual monthly heatmap with color intensity based on completion rates. Click any date to view and backfill habits for that day!

### 🎯 Daily Productivity & Reflections
- **Daily Reflection & Mood Journal:** Track your mood (🤩, 😊, 😐, 🥱, 😔) and save daily reflections and gratitude notes.
- **Action Tasks (To-Do List):** Integrated task list with priority badges (*Urgent* / *Normal*), filters (*Active* / *Done*), and 1-click cleanup.
- **Daily Motivational Quotes:** Inspiring rotating daily quotes from thinkers and authors like James Clear, Aristotle, and Seneca.

### 🎨 Modern Experience & Data Portability
- **🌙 Light / Dark Mode:** Seamless, persistent theme switcher that is easy on the eyes.
- **🔔 Audio & Confetti Celebrations:** Synthesized Web Audio chime and particle confetti bursts when reaching milestones or 100% daily completion.
- **💾 JSON Backup & Restore:** 1-click export and import of your entire habits, logs, reflections, and to-do history.
- **⚡ 100% Offline & Zero Dependencies:** Pure HTML5, CSS3, and modern vanilla JavaScript. No heavy frameworks, no external CDN tracking, lightning fast.

---

## 🚀 Quick Start (Run Locally via CLI)

### Option 1: Python HTTP Server (Recommended)

Run directly from your terminal or command prompt:

```powershell
# Navigate to repository directory
cd path/to/HABITTRACKER

# Start Python local web server
python -m http.server 8000
```

Open your browser and navigate to:
```
http://localhost:8000
```

### Option 2: Node.js / npx `serve` or `http-server`

```bash
npx serve .
# or
npx http-server -p 8000
```

### Option 3: Direct Browser Launch

Since HabitFlow is fully self-contained, you can double-click `index.html` or open it directly:

```powershell
Start-Process index.html
```

---

## 📁 Project Structure

```text
HABITTRACKER/
├── index.html       # Complete application (UI, CSS variables, theme engine, Canvas chart, JS logic)
├── README.md        # Documentation and guide
└── .gitignore       # Git ignore rules
```

---

## 🛠️ Data Storage & Privacy

All your data is stored locally in your web browser via `localStorage` under the key `habitflow-data-v2`. No personal data ever leaves your device. You can easily back up or transfer your data across devices using the built-in **Backup** (JSON Export) and **Restore** (JSON Import) buttons in the header.

---

## 🤝 Contributing

Contributions, feature requests, and suggestions are welcome!
Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).