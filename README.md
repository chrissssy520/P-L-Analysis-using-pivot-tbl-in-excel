# 📊 Project P&L Dashboard — Excel

An interactive **Profit & Loss Dashboard** built in Microsoft Excel, analyzing budget vs. actual performance across 15 projects, 5 regions, and 3 years (2022–2024).

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

---

## 📸 Preview

> *Interactive P&L Dashboard with KPI cards, variance analysis, and dynamic slicers*

---

## 📁 Project Structure

```
📦 PL-Dashboard
 ┣ 📄 PL_Dataset_500rows.xlsx   # Raw dataset (500 rows)
 ┣ 📄 PL_Dashboard.xlsx         # Final dashboard with pivot table
 ┗ 📄 README.md
```

---

## 📌 Features

- ✅ **P&L Structure** — Revenue, COGS, Gross Profit, Expenses, Net Profit
- ✅ **Budget vs Actual** comparison across all projects
- ✅ **Variance & Variance %** — highlights over/under performance
- ✅ **Profit Margin** row (Budget vs Actual)
- ✅ **KPI Cards** — Total Revenue & Total Profit at a glance
- ✅ **Dynamic Slicers** — filter by Year (2022–2024) and Region
- ✅ **Philippine Peso (₱)** currency formatting
- ✅ Conditional formatting — red for negative variance

---

## 🗂️ Dataset Overview

| Column | Description |
|--------|-------------|
| Project | 15 unique project names |
| Region | North, South, East, West, Central |
| Year | 2022, 2023, 2024 |
| Month | Jan – Dec |
| Category | Revenue, COGS, Expenses |
| Actual | Actual amount recorded |
| Budget | Budgeted amount |

**500 rows** of transactional P&L data across all dimensions.

---

## 🧮 Calculated Fields (Pivot Table)

| Field | Formula |
|-------|---------|
| Variance | `Actual - Budget` |
| Variance % | `(Actual - Budget) / Budget` |
| Gross Profit | `Revenue - COGS` |
| Net Profit | `Gross Profit - Expenses` |
| Profit Margin | `Net Profit / Revenue` |

---

## 🛠️ Tools Used

- **Microsoft Excel** — Pivot Tables, Calculated Fields, Slicers
- **Power Query** — Data transformation and reshaping

---

## 💡 Key Insights

- Total Actual Revenue: **₱44,581,610.11** vs Budget **₱44,695,742.58** (-0.26%)
- Total Net Profit: **₱16,604,167.04** vs Budget **₱17,966,567.65** (-7.58%)
- Actual Profit Margin: **37%** vs Budgeted **40%** (-3%)
- **Lambda Gate** had the highest COGS variance at +9.75%

---

## 🚀 How to Use

1. Download `PL_Dashboard.xlsx`
2. Open in Microsoft Excel (2016 or later recommended)
3. Use the **Year** and **Region** slicers to filter the dashboard
4. All calculated fields update dynamically

---

## 👤 Author

Built as a portfolio project demonstrating Excel financial modeling and dashboard design skills.
