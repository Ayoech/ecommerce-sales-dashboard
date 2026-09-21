# Ecommerce Sales Dashboard (Excel)

An interactive Excel dashboard analyzing ecommerce sales performance across regions, payment methods, and discount strategies using PivotTables, PivotCharts, Timeline controls, and Slicers.

## Business Question
Which regions, discount tiers, and payment methods drive the majority of revenue, and how did overall sales performance evolve between 2022 and 2025?

## Key Insights & Business Takeaways
* **Regional Dominance:** The **West region** generated the highest total sales (~$1.35M), outperforming the **North region** (~$1.28M) and vastly exceeding the **East region** (~$1.21M)[cite: 2].
* **Discount Tier Distribution:** The **High discount tier** represents the largest share of overall sales (over 35% of revenue based on the breakdown), followed by the **Low** and **Medium** tiers[cite: 2]. Revenue from the **No Discount** tier remains negligible[cite: 2].
* **Massive Growth Surge (Late 2024 / Early 2025):** Monthly sales exploded from a historical baseline of **~$10,000–$20,000/month** (2022–2024) to peak between **$120,000–$150,000/month** in early 2025, primarily driven by high and medium discount promotion campaigns[cite: 2].
* **Payment Preference:** Wallet transactions and Card payments represent the dominant share of high-volume sales periods compared to COD[cite: 2].

## Data Summary
* **Timeline Covered:** October 2022 – September 2025 (Monthly granularity)[cite: 2].
* **Data Cleaning & Validation:** Corrected anomalous date entries (e.g., future-dated records in 2035 adjusted to 2025) to maintain timeline consistency, removed empty fields, and standardized discount tier categories[cite: 2].

## Dashboard Layout
![Ecommerce Sales Dashboard](screenshots/dashboard-overview.png)

## Interactive Features & Excel Tools
* **Timeline Control:** Dynamic monthly slider filtering for periods between Oct 2024 and Sep 2026[cite: 2].
* **Slicers:** Interactive filtering for **Payment Method** (`Card`, `COD`, `Wallet`) and **Discount Tier** (`High`, `Medium`, `Low`, `No Discount`)[cite: 2].
* **PivotCharts & Visuals:**
  * Multi-line trend graph tracking monthly sales volume across discount tiers[cite: 2].
  * Proportional pie chart for discount tier revenue contribution[cite: 2].
  * Horizontal bar chart ranking total sales by geographic region[cite: 2].

## File
* [`ecommerce_sales_dashboard.xlsx`](ecommerce_sales_dashboard.xlsx) — Download to explore interactive filters and PivotTables[cite: 2].
