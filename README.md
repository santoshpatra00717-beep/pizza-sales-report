# 🍕 Pizza Sales Report — Tableau Dashboard

An interactive Tableau dashboard analyzing a full year of pizza sales data (2015), covering revenue trends, 
order patterns, peak business hours, and performance by pizza category and size.

## 📌 Overview

This dashboard was built to help a pizza business understand **when** customers order, **what** they order, 
and **where** the biggest sales opportunities lie — turning raw transactional data into a decision-ready 
executive view.

## 🔑 Key Metrics

| Metric | Value |
|---|---|
| Total Revenue | $817.9K |
| Total Pizzas Sold | 49.6K |
| Total Orders | 21.4K |
| Avg Order Value | $38.3 |
| Avg Pizzas per Order | 2.32 |

## 📊 Dashboard Components

- **Hourly Trend for Pizzas Sold** — Stacked bar chart showing order volume by hour and pizza category (Chicken, Classic, Supreme, Veggie)
- **Weekly Trend for Total Orders** — Line chart tracking order volume across all 52 weeks of the year
- **Busiest Hours & Weeks** — Callout panel highlighting peak ordering windows and seasonal spikes
- **Percentage of Sales by Pizza Category** — Donut chart breaking down revenue share across Classic, Chicken, Supreme, and Veggie
- **Percentage of Sales by Pizza Size** — Distribution across Regular, Medium, Large, X-Large, and XX-Large
- **Total Orders & Pizzas Sold by Category** — Table comparing order count vs. units sold per category
- **Sales Performance Summary** — Key takeaways on top-performing category and size

## 💡 Key Insights

- **Peak ordering hours**: 12:00–1:00 PM (lunch) and 4:00–7:00 PM (dinner)
- **Highest weekly peak**: Week 48 (late November/December)
- **Classic** is the top-performing category — highest sales, orders, and pizzas sold
- **Large** is the best-selling pizza size, driving the most total sales
- Category sales are fairly balanced: Classic (30.0%), Supreme (24.2%), Veggie (23.5%), Chicken (22.3%)
- Pizza size skews heavily toward Large (45.9%) and Medium (30.5%), with XX-Large barely used (0.12%)

## 🛠️ Tools Used

- **Tableau** (Desktop/Public) — dashboard design, calculated fields, filters, and visualizations
- **Data source**: Pizza sales transactional dataset (order date, category, size, revenue, quantities)

## 🔗 Live Dashboard

👉 [View the interactive dashboard on Tableau Public](#) <!-- replace with your Tableau Public link -->

## 📂 Repo Contents

├── pizza_sales_dashboard.twbx    # Tableau packaged workbook
├── pizza_sales_data.csv          # (optional) source dataset
├── dashboard_screenshot.png      # Preview image
└── README.md

## 🚀 How to View

1. Download `pizza_sales_dashboard.twbx`
2. Open in [Tableau Desktop](https://www.tableau.com/products/desktop) (free trial available) or [Tableau Public](https://public.tableau.com/) (free)
3. Or click the live dashboard link above to explore directly in your browser

---

**Author**: Santosh Kumar Patra
