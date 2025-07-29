# 💼 Freelance Tracker 📊

A lightweight and customizable Excel-based tool to help freelancers track project status, payments, and overall productivity — built for real-world efficiency with added formulas and visuals.

---

## 📌 Features

- ✅ **Project Status Tracking** – See which projects are completed, ongoing, or pending.
- 💸 **Invoice Sent Check** – Auto-flag completed projects where invoice hasn't been sent.
- 📈 **Insights Dashboard** – Visual representation of project progress and revenue summary.
- 🧠 **Smart Formulas** – Custom logic to highlight missing actions (e.g., invoice not sent).
- ⚠️ **Dummy Data Used** – For privacy, all data shown is mock for demonstration purposes.

---

## 🚀 Getting Started

1. **Clone this repo** or download the Excel file.
2. Open in **Microsoft Excel** (Web or Desktop).
3. Explore the two sheets:
   - **Data Sheet** – where you enter project details.
   - **Dashboard** – where visual analysis happens automatically.

---

## ⚙️ Formula Highlights

```excel
=IF(AND([@Status]="Completed", [@[Invoice Sent]]="No"), "Not Sent", "")
