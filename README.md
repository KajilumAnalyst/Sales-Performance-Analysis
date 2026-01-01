# Sales Performance Analysis Dashboard

## Project Objectives
This dashboard visualizes key sales metrics for the second quarter (Q2), providing actionable insights into sales trends, popular products, and customer payment behaviors. The goal is to enable data-driven decision-making by tracking performance, identifying top-selling products, and understanding purchasing patterns.

## Dataset Used
- <a href= "https://github.com/KajilumAnalyst/Sales-Performance-Analysis/blob/main/sales_transactions-2026-01-01.csv">Dataset Used</a>

## Key Business Questions (KPIs)
- How did sales volume trend throughout Q2?
- What is the most popular product by sales volume?
- How do customers prefer to pay?
- What does the payment method distribution look like? 
- Which products contribute most to overall sales quantity?
- Were there specific high or low sales points in the quarter?

- Dashboard Interaction <a href = "https://github.com/KajilumAnalyst/Sales-Performance-Analysis/blob/main/dash.png">View Dashboard</a>
  
## Processes
- Cleaned and prepared raw sales transaction data using SQL to ensure accuracy and structure.
- Engineered key metrics, including weekly sales totals, product-level quantity aggregates, and payment method frequencies.
- Analyzed the processed time-series data to identify weekly patterns, peaks, and troughs in sales performance.
- Selected appropriate chart types (line, bar, pie) to effectively represent trends, comparisons, and part-to-whole relationships.
- Integrated individual charts into a cohesive, single-view layout using Bigquery visualization tool

## Dashboard
<img width="975" height="530" alt="image" src="https://github.com/user-attachments/assets/93c76357-eec2-4452-a756-eae271fce480" />

## Project Insights
- Volatile Weekly Sales: The quarter started strong but showed significant week-to-week fluctuations.
- Dominant Top Product: Golden Gate Ginger is the clear sales leader with 3870 quantity sold. 
- Tlght Mid-Tier Competition: The next five products have very similar sales volumes.
- Payment Preference: Credit card usage dominates, with Mastercard asthe leading network.

## Conclusion & Recommendations
The Q2 sales performance indicates a healthy product portfolio with a strong market favorite in Golden Gate Ginger. However, the observed weekly volatility in sales volume presents a key opportunity for stabilization.

Recommendations:

- Investigate Weekly Dips by conducting a deep-dive into the low-sales weeks (belo 1.2K units) to identify root causes such as inventory, marketing silence, or external competition.
- Leveraging Top Product by capitalizing on the popularity of Golden Gate Ginger through featured promotions  deals to help uplift sales during typically slower weeks.
- Implement targeted marketing strategies for products like "Orchard Oasis" (3.59K units) to narrow the gap with top sellers.
