# Hi, I'm Yunus Dağ 👋

Public sector professional (energy field) moving into **data analytics, database management, and process automation**. I build real, working tools for real day-to-day problems instead of tutorial projects.

📍 İzmir, Turkey · ✉️ yunusdag_92@outlook.com

---

## 🎯 Current Focus

- **Databases & data analysis** — hands-on with SQL Server and SQLite, working toward database administration and data analyst roles
- **Process automation** — desktop tools that replace manual, error-prone routines
- **Formal education** — pursuing a software engineering degree track alongside self-directed project work

---

## 🛠️ Tech Stack

| | |
|---|---|
| **Languages** | `Python` `SQL` `JavaScript` |
| **Data** | `SQL Server` `SQLite` `Power BI` `Microsoft Excel` |
| **Tools** | `Git` `GitHub` `Electron / Node.js` `PyInstaller` |

---

## 🚀 Featured Projects

### [faturatakip](https://github.com/yunusdag-dev/faturatakip) — Purchase invoice registry for a team
A Windows desktop app (Python, tkinter, SQLite) that a small team uses on a shared network folder to register and track purchase invoices.

<img src="assets/fatura-takip.png" width="720" alt="Fatura Takip screenshot (sample data)">

- 📄 **Reads invoice PDFs and fills the form** — date, invoice number, supplier, tax ID, amounts; the user always verifies before saving
- 🔎 **Multi-page scans** — finds the invoice page automatically among up to 20 pages (page scoring), with manual override
- 🖨️ **Layered extraction** — PyMuPDF, then a stdlib-only PDF text parser, then Windows OCR for scanned pages
- 🗄️ **Shared SQLite database** on a network share, with clear error handling for locked files
- 💰 **Money stored as integer kuruş** — no floating-point rounding errors
- 📊 **Formatted Excel export** — real date/number cells, totals, filters, print setup
- 📦 **Shipped as a standalone `.exe`** (PyInstaller) — no Python needed on users' machines

### [gelir-gider-app](https://github.com/yunusdag-dev/gelir-gider-app) — Personal finance desktop app
A full-featured budgeting application (Windows, Electron/Node.js), built in phases:
- 📊 Income/expense tracking with categorized budgeting and limit alerts
- 🎨 Theme system (dark/light/ocean)
- 📅 Custom date-range financial reports
- 📁 Excel & PDF export (in progress)
- 🎯 Savings goals module with automated rounding rules

Built end-to-end — from data model to UI to reporting — as a tool I use myself.

---

## 📫 Let's connect

I'm open to **data analyst, database, and automation** opportunities. Feel free to reach out by email.
