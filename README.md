# Ecommerce Sales Dashboard (Excel)

An interactive Excel dashboard analyzing ecommerce sales performance across regions, payment methods, and discount strategies using PivotTables, PivotCharts, Timeline controls, and Slicers.

## Business Question
Which regions, discount tiers, and payment methods drive the majority of revenue, and how did overall sales performance evolve between 2022 and 2025?

## Key Insights & Business Takeaways
* **Regional Dominance:** The **West region** generated the highest total sales (~$1.35M), outperforming the **North region** (~$1.28M) and exceeding the **East region** (~$1.21M).
* **Discount Tier Distribution:** The **High discount tier** accounts for the largest share of overall sales, followed by the **Low** and **Medium** tiers, while the **No Discount** tier generated minimal revenue.
* **Massive Growth Surge (Late 2024 / Early 2025):** Monthly sales increased sharply from a baseline of **~$10,000–$20,000/month** (2022–2024) to peak between **$120,000–$150,000/month** in early 2025, driven by promotional discount tiers.
* **Payment Preference:** Wallet and Card transactions represent the dominant payment methods across high-volume sales periods compared to COD.

## Data & Cleaning Process
* **Timeline Covered:** October 2022 – September 2025 (Monthly granularity).
* **Data Cleaning & Validation:** Performed comprehensive data cleaning including handling missing values, standardizing discount tier categories, and correcting entry anomalies (e.g., adjusting future-dated records from 2035 to 2025) to ensure full timeline consistency.

## Dashboard Layout
![Dashboard Screenshot](screenshots/dashboard-overview.png)

## Interactive Features & Excel Tools
* **Timeline Control:** Dynamic monthly slider filtering across sales periods.
* **Slicers:** Interactive filtering for **Payment Method** (`Card`, `COD`, `Wallet`) and **Discount Tier** (`High`, `Medium`, `Low`, `No Discount`).
* **PivotCharts & Visuals:**
  * Multi-line trend graph tracking monthly sales volume across discount tiers.
  * Proportional pie chart for discount tier revenue contribution.
  * Horizontal bar chart ranking total sales by geographic region.

## Tools & Skills
* **Excel:** PivotTables, PivotCharts, Slicers, Timeline controls, custom number formatting, dashboard design.
* **Data Engineering & Analysis:** Data cleaning, data validation, trend analysis, categorical aggregation.

## File
* [`dashboard.xlsx`](dashboard.xlsx) — Download to explore interactive filters and PivotTables yourself.
