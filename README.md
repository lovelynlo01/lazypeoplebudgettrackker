# Duit 💸
### Budget Tracker for Messy Brains & Lazy Planners 😌

> Track your money in under 10 seconds. No stress, no spreadsheets.

A lightweight, single-file personal budget tracker that runs entirely in your browser. No backend, no database, no sign-up required. Just open the page and start logging.

---

## ✨ Features

- **Two income sources** — track your main salary and any secondary income separately
- **Fixed monthly expenses** — set recurring costs like rent and car loans once, forget about them
- **Daily spending log** — add entries on the fly with quick-tap category chips (Food 🍜, Transport 🚗, Groceries 🛒, and more)
- **Live signals** — instant green / amber / red status indicators that update as you type
- **Savings threshold** — set your own minimum savings floor; get alerted the moment you're approaching it
- **Balance box** — a clear, human-readable summary: *Safe 😌 / Tight 😬 / Overspending 🚨*
- **3 chart views** — daily spending bar chart, budget overview, and expense breakdown doughnut
- **Auto-save** — all data is saved automatically to your browser's local storage
- **Export / Import** — download your data as a JSON file to transfer between devices, then import it back in one click
- **Reset Month** — clear your daily entries at the start of each month with one button

---

## 🚀 Getting Started

No installation needed.

1. Download `budget-tracker.html`
2. Open it in any modern browser
3. Start logging

Or visit the live GitHub Pages link: `[your-github-pages-url-here]`

---

## 📱 Using Across Multiple Devices

Since data is saved locally in your browser, it doesn't automatically sync between devices. To move your data:

1. On your current device, click **📤 Export** — this downloads a `.json` file
2. Send the file to your other device (email, WhatsApp, Google Drive, AirDrop — anything works)
3. On the new device, open the tracker and click **📥 Import**
4. Pick the file — your data loads instantly

> **Note:** Local storage is tied to a specific browser on a specific device. Using Chrome on your laptop and Safari on your phone means two separate data stores.

---

## 🗂️ How It Works

Everything lives in a single `.html` file. There is no server, no cloud sync, and no third-party data collection. Your financial data never leaves your device unless you choose to export it.

Data is stored using the browser's `localStorage` API under the key `duit_budget_v1`.

---

## 🔄 Monthly Reset Workflow

At the start of each new month:

1. Hit **📤 Export** to archive the previous month's data
2. Click **🔄 Reset month** to clear daily entries
3. Your income and fixed expenses carry over automatically

---

## 🛠️ Built With

- Vanilla HTML, CSS, and JavaScript — no frameworks
- [Chart.js](https://www.chartjs.org/) — for the interactive charts
- [DM Sans + DM Serif Display](https://fonts.google.com/) — Google Fonts
- Browser `localStorage` — for auto-save

---

## 📋 Planned / Possible Upgrades

- [ ] Cloud sync via Supabase or Firebase (for seamless multi-device use)
- [ ] Monthly archive view (browse past months)
- [ ] Spending category budget limits
- [ ] Dark mode

---

## 📄 License

This project is open for personal use. Feel free to fork, modify, and make it your own.

---

*Made with ☕ and a healthy disregard for complicated budgeting apps.*
