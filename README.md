# 🛒 Elite FurniShop Analytics — Superstore Sales Dashboard

<img width="1613" height="901" alt="image" src="https://github.com/user-attachments/assets/68b0373e-c9cc-450c-9baa-8c97a460bdc1" />


## 📌 Project Overview

An interactive **Tableau dashboard** analyzing US Superstore retail sales data across 4 regions, 3 product categories, and 17 sub-categories. The dashboard enables dynamic cross-filtering — clicking any chart instantly updates all other visuals.

---

## 🎯 Business Problem

A US retail company needed a centralized analytics solution to:
- Monitor overall sales performance and revenue trends
- Identify top-performing products, categories, and regions
- Understand customer segment behavior
- Track shipping mode preferences over time

---

## 📊 Dashboard Features

| Visual | Type | Insight |
|--------|------|---------|
| Sales Trend | Line Chart | Monthly revenue pattern across the year |
| Sales by Category | Bar Chart | Technology vs Furniture vs Office Supplies |
| Sales by Segment | Pie Chart | Consumer vs Corporate vs Home Office share |
| SubCategory Breakdown | Treemap | All 17 sub-categories sized by revenue |
| Product with Ship Mode | Clustered Bar | Top products by delivery method |
| Top 10 Products | Horizontal Bar | Highest revenue generating products |
| Sales by State | Geographic Map | US state-level sales distribution |
| Total Sales | KPI Card | $2.26M total revenue |
| Total Orders | KPI Card | 9,800 orders processed |
| Avg Order Value | KPI Card | $459.48 per order |
| Total Customers | KPI Card | 4,922 unique customers |

---

## 🔍 Key Insights

- 📱 **Technology** leads all categories with **$827K** in sales
- 🌍 **West region** drives the highest sales volume across the US
- 🖨️ **Canon imageCLA** is the top product with **$61K** in revenue
- 👥 **Consumer segment** accounts for the largest share of purchases
- 📈 Sales show a **consistent upward trend** toward year-end
- 🚚 **Standard Class** is the most preferred shipping method

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Tableau Desktop | Dashboard creation and visualization |
| Microsoft Excel / CSV | Data source |
| GitHub | Version control and portfolio hosting |
| Kaggle | Dataset and notebook publishing |

---

## 📁 Dataset Information

| Field | Details |
|-------|---------|
| Dataset | Sample Superstore Sales |
| Source | Kaggle / Tableau Sample Data |
| Records | 9,994 orders |
| Time Period | Full year (January — December) |
| Regions | West, East, Central, South |

**Columns used:**
`Row_ID`, `Order_ID`, `Order_Date`, `Ship_Date`, `Ship_Mode`, `Customer_ID`, `Customer_Name`, `Segment`, `Country`, `City`, `State`, `Postal_Code`, `Region`, `Product_ID`, `Category`, `Sub_Category`, `Product_Name`, `Sales`

---

## 🖥️ How to View the Dashboard

### Option 1 — View Screenshot
Open `superstore_dashboard.png` in this repository

### Option 2 — Open in Tableau
1. Download `superstore.twbx` from this repository
2. Open with **Tableau Desktop** or **Tableau Public** (free)
3. Interact with the dashboard — click any chart to cross-filter!

### Option 3 — Tableau Public (Online)
> Link: *(paste your Tableau Public link here after publishing)*

---

## 🎨 Design Decisions

- **Dark navy theme** (`#1A1A2E`) — professional and modern
- **Gold line chart** (`#F6AE2D`) — stands out on dark background
- **Steel blue bars** (`#2E86AB`) — clean and consistent
- **Multicolor treemap** — distinct colors for all 17 sub-categories
- **Cross-filter interactions** — all charts linked for dynamic exploration

---

## 📂 Repository Structure

```
superstore-sales-dashboard/
│
├── superstore_dashboard.png    ← Dashboard screenshot
├── superstore.twbx             ← Tableau packaged workbook
├── superstore.csv              ← Raw dataset
└── README.md                   ← This file
```

---


## ⭐ If you found this helpful, please star this repository!
