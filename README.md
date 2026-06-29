# 📊 Sales Dashboard 2026

A Microsoft Excel workbook that analyses and visualises sales transaction data across products, regions, and sales personnel — built for quick, data-driven decision-making.

---

## 📁 Project Structure

```
├── SalesDashboard.xlsx        # Main Excel workbook
│   ├── SalesData              # Raw transaction records
│   ├── Pivot Tables           # Summarised analysis & charts
│   └── Dashboard              # Interactive visual summary
│
├── Documentation/
│   └── Project_Report.docx    # Full project documentation
│
└── README.md                  # You are here
```

---

## 🗂️ What's Inside

### Sheet 1 — SalesData
The raw data source. Every row is one sales transaction with these columns:

| Column | Description |
|--------|-------------|
| Date | Date of the sale |
| Sales Person | Employee who made the sale |
| Region | East / West / North / South |
| Product | Item sold |
| Units Sold | Quantity per transaction |
| Unit Price | Price charged per unit (Rs.) |
| Cost of Goods | Company's cost per unit (Rs.) |
| Total Sales | Units Sold × Unit Price |
| Profit | Total Sales − Cost of Goods |

> **Data period:** February 2021 – December 2021

---

### Sheet 2 — Pivot Tables
Four pivot tables that summarise the raw data:

- **By Region** — total sales per territory
- **By Product** — revenue and units per product category
- **By Sales Person** — individual performance totals
- **Units Sold by Product** — volume comparison across all 7 products

> To refresh after adding new data: right-click any pivot → **Refresh All**

---

### Sheet 3 — Dashboard
A single-page visual overview with four charts and interactive filters.

**Charts:**
- Line chart — Units sold by product
- Bar chart — Total sales by product
- Donut chart — Regional sales share
- Bar chart — Sales by sales person

**Slicers (interactive filters):**
- `Product` — filter all charts by one or more products
- `Sales Person` — filter all charts by one or more team members

> To clear a filter: click the **funnel icon** on the slicer or press `Alt + C`

---

## 📈 Key Numbers (Full Dataset)

| Metric | Value |
|--------|-------|
| Total Sales | Rs. 1,29,44,500 |
| Total Profit | Rs. 38,34,400 |
| Units Sold | 4,705 |
| Average Sales | Rs. 2,58,890 |

---

## 🏆 Quick Insights

- **Top Region:** West — Rs. 38,78,100
- **Top Product by Revenue:** Sneakers — Rs. 31,96,000
- **Top Product by Volume:** Moisturizer — 1,178 units
- **Top Sales Person:** Grace — Rs. 19,57,000
- **Lowest Region:** North — Rs. 26,61,400
- **Lowest Product:** Action Figure — Rs. 5,47,200

---

## 🚀 How to Use

1. Open the file in **Microsoft Excel 2016 or later**
2. Go to the **Dashboard** tab for a visual overview
3. Use the **slicers** to filter by product or sales person
4. Visit **Pivot Tables** for detailed breakdowns
5. Add new rows to **SalesData** and refresh pivots to update everything

---

## 📋 Requirements

- Microsoft Excel 2016 or later (slicers and pivot charts require this)
- No macros or external dependencies

---

## 📄 Documentation

Full project documentation including analysis, insights, and glossary is available in:
```
Documentation/Project_Report.docx
```

---

