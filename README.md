# 📊 Excel Personal Finance Tracker

This is a dynamic, Excel-based personal finance tracker designed to help users monitor income, expenses, and savings over time. It uses slicers, PivotTables, and lookup functions to provide an automated and interactive dashboard for personal budgeting.

---

## 🧩 Features

### ✅ Interactive Dashboard
- Slicers to filter data by **Year**, **Month**, and **Account**
- PivotTables displaying:
  - Total **Income**
  - Total **Expenses**
  - **Expenses by Category**
  - **Income by Month**
  - **Expense by Month**
  - **Net Savings Overview**

### 📄 Bank Transactions Tab
Tracks all financial activity with the following columns:
- **Account Type** (e.g. Checking, Credit)
- **Date**
- **Debit / Credit**
- **Income - Expense** logic
- **Subcategory** (with **data validation dropdown** from base data)
- **Category** (via `XLOOKUP` from subcategory list)
- **Category Type** (e.g., Fixed, Variable) from a raw data reference table

### 🔁 Automation Features
- `XLOOKUP`-driven Category and Type mappings
- Pre-built PivotTables auto-refresh on data updates
- Slicers that sync across multiple charts and tables

---

## 📷 Screenshots

| Dashboard View | Transaction Tab | Category Mapping |
|----------------|------------------|------------------|
| ![Dashboard](./screenshots/dashboard_view.png) | ![Transactions](./screenshots/bank_transactions_tab.png) | ![Categories](./screenshots/category_flow.png) |

---

## 🛠️ How to Use

1. Clone or download the repository.
2. Open `Personal_Finance_Tracker.xlsx` in Excel (2016+ recommended).
3. Go to the **Bank Transactions** tab and paste in your bank data.
4. Add new subcategories if needed in the **Raw Data** sheet.
5. Dashboard updates automatically with slicers and charts.

---

## 💡 Future Enhancements (Ideas)
- Conditional formatting for spending alerts
- Monthly budget caps by category
- Integration with CSV/OFX bank exports (via Power Query)
- Optional Power BI extension

---

## 📜 License

MIT License (or specify your own)
