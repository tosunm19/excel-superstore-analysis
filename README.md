# Excel Sales, Shipping & Returns Dashboard

## Project overview
This project showcases an **advanced Excel dashboard** built on the classic *Superstore* dataset.  
The goal is to analyze **commercial performance**, **shipping efficiency**, and **return behavior** in a single, interactive view.

The dashboard is fully built in **Microsoft Excel**, using Power Query and the Excel Data Model (Power Pivot), and is designed to be intuitive, reproducible, and recruiter-friendly.

---

## Key business questions
- How are sales and profitability evolving over time?
- Which product categories drive margin — and which destroy it?
- Where does shipping performance lag at meaningful volume?
- Which products have the highest return rates, and do they matter financially?

---

## Tools & techniques (Excel only)
- **Power Query** for data ingestion, cleaning, and transformations  
- **Excel Data Model (Power Pivot)** for relationships and calculations  
- **DAX measures**, including:
  - Total Sales
  - Total Profit
  - Profit Margin %
  - Orders
  - Return Rate %
  - Average Ship Days
- **PivotTables & PivotCharts**
- **Slicers** for interactivity
- **KPI cards with sparklines** for compact trend visualization

---

## Dashboard contents
- Monthly sales trend
- Profit margin by product category
- Shipping performance (volume vs lead time)
- Return rate hotspots (Top 10 sub-categories)
- Impact table combining returns, sales, and profit

---

## Key insights
- Sales show clear seasonality with stronger performance in Q4.
- Certain sub-categories combine **high return rates and high sales volume**, creating disproportionate profit leakage.
- Slower shipping modes are acceptable at low volume but become critical bottlenecks at scale.
- High discount levels correlate with structurally lower profit margins in selected categories.

---

## Limitations
- Shipping SLA is inferred from *Order Date* vs *Ship Date* (no promised delivery date available).
- The dataset represents historical sample data and does not reflect a live operational system.

---

## How to use
1. Download `superstore_dashboard.xlsx` from the `workbook/` folder.
2. Open the file in Excel.
3. Use slicers (Year, Region, Segment, Category, Ship Mode) to explore the dashboard interactively.

