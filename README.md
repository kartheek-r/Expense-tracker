# 💰 Expense Tracker — HTML, CSS & JavaScript

> A responsive **Expense Tracker web app** built with vanilla HTML, CSS, and JavaScript that lets users add income and expenses, calculate balances in real-time, and persist all data using LocalStorage — no backend, no frameworks, no setup required.

---

## 📌 Project Overview

Managing personal finances doesn't need a complex app — it just needs a clean, fast, and reliable interface. This Expense Tracker solves that by giving users a simple way to log every income and expense transaction, watch their balance update instantly, and come back to their data exactly where they left off — all powered by the browser's own LocalStorage.

---

## ✨ Features

- ➕ Add **income and expense** transactions with a description and amount
- 💡 **Positive amount** → logged as Income | **Negative amount** → logged as Expense
- 📊 **Real-time balance** — total balance updates instantly on every transaction
- 🟢 Live **Income summary** and 🔴 **Expense summary** displayed separately
- 🗑️ **Delete any transaction** from the history list
- 💾 **LocalStorage persistence** — data survives page refreshes and browser restarts
- 📱 Fully **responsive UI** — works seamlessly on desktop, tablet, and mobile

---

## 🏗️ How It Works

```
User enters transaction description + amount
        ↓
Positive value  →  Classified as Income (green)
Negative value  →  Classified as Expense (red)
        ↓
script.js  →  Adds transaction to the list dynamically
        ↓
DOM updates:
  1. Transaction appears in history list
  2. Balance recalculates in real-time
  3. Income total updates
  4. Expense total updates
        ↓
LocalStorage  →  Saves all transactions to browser storage
        ↓
On page reload  →  Transactions restored from LocalStorage automatically
```

---

## 📂 Project Structure

```
Expense-tracker/
│
├── index.html            # App structure & layout
├── style.css             # Styling & responsive design
├── script.js             # Core logic — CRUD, balance calc, LocalStorage
├── expense-tracker.jpeg  # App UI screenshot
└── README.md             # Project documentation
```

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| 🏗️ Structure | HTML5 |
| 🎨 Styling | CSS3 |
| ⚙️ Logic & Interactivity | JavaScript (ES6+) |
| 💾 Data Persistence | Web LocalStorage API |

---

## 🖼️ App Preview

![Expense Tracker Preview](expense-tracker.jpeg)

---

## ▶️ How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/kartheek-r/Expense-tracker.git
cd Expense-tracker
```

### 2. Open in Browser
No installation or build step needed — just open the HTML file directly:

```bash
# Option A — double-click index.html in your file explorer

# Option B — open from terminal (Mac/Linux)
open index.html

# Option C — open from terminal (Windows)
start index.html
```

### 3. Start Tracking
- Enter a **transaction name** and **amount**
- Use a **positive number** for income (e.g. `+2000`)
- Use a **negative number** for an expense (e.g. `-500`)
- Click **Add Transaction**
- Your balance, income total, and expense total update instantly

---

## 📊 Sample Output

After adding transactions, you see:

| Section | What You Get |
|---------|--------------|
| 💳 Balance Card | Live total balance (income minus expenses) |
| 🟢 Income Total | Sum of all positive transactions |
| 🔴 Expense Total | Sum of all negative transactions |
| 📋 Transaction History | Colour-coded list of all added transactions |
| 🗑️ Delete Button | Remove any transaction and auto-recalculate |

---

## 💡 Use Cases

- 🎓 Students tracking daily spending and pocket money
- 💼 Freelancers logging project income and business costs
- 🏠 Anyone managing household income and monthly bills
- 🧑‍💻 Developers learning DOM manipulation, event handling, and LocalStorage

---

## 🔮 Future Scope

- 📂 Add **expense categories** (Food, Travel, Bills, etc.)
- 📊 Visual **charts and graphs** for spending breakdown
- 📅 **Date filtering** — view transactions by day, week, or month
- 🌐 Deploy on **GitHub Pages** for instant public access
- 📥 **Export transactions** as CSV or PDF report
- 🔐 User **authentication** for multi-device sync

---

## 🙌 Conclusion

This project demonstrates how much can be built with just three core web technologies — HTML, CSS, and JavaScript. From real-time DOM updates to persistent browser storage, the Expense Tracker covers essential front-end development concepts in a practical, everyday-use application. A clean project for any web development portfolio.

---

## 👨‍💻 Author

**Ryalampadu Kartheek**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kartheek-ryalampadu)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kartheekryalampadu@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kartheek-r)
