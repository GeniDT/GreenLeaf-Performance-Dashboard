# GreenLeaf-Performance-Dashboard - – Using Power BI
The GreenLeaf Performance Dashboard is a data-driven analytics tool that offers insights into sales trends, product performance, and profitability. Built using Power BI, this dashboard helps stakeholders track key metrics, identify growth opportunities, and make informed management decisions.


## Dataset used
- <a href="https://github.com/GeniDT/GreenLeaf-Performance-Dashboard/blob/main/Plant_DTS.xlsx">Dataset</a>


## Business Questions
- How has GreenLeaf’s Year-to-Date (YTD) sales revenue changed compared to the Prior Year-to-Date (PYTD)?
- Which countries contributed most to sales growth or decline?
- How has GreenLeaf’s total sales quantity changed over time?
- Which product categories contributed most to the total quantity sold?
- What is the relationship between sales quantity and profitability?
- How can GreenLeaf optimize sales and inventory management using data-driven insights?

## Dashboard Preview
![Image](https://github.com/user-attachments/assets/247c16b1-f676-4a23-988b-bc797d2493b8)


## Process
- Imported raw data and performed data transformation (removing duplicates, handling missing values, and correcting data types) using Power Query.
- Created new calculated columns where necessary (e.g., YTD, PYTD, and growth metrics).
- Established relationships between tables 
- Defined measures using DAX to calculate KPIs like YTD Sales, PYTD Sales, and GP %.
- Designed an interactive dashboard layout with charts, slicers, and key metrics.
- Implemented slicers for Sales, Quantity, and Gross Profit to allow flexible analysis.
- Adjusted colors, spacing, and layout for clarity.


## Key Insights & Findings
-How did sales perform year over year?

2024 YTD sales revenue is lower than 2023’s PYTD sales, indicating a decline in total revenue.
The YTD vs. PYTD Sales Growth metric shows a negative trend, suggesting that sales performance has slowed in early 2024.
Seasonal trends were observed, with higher sales in certain months of 2023 compared to the same period in 2024.

- Which product categories performed best and worst?

Outdoor plants remained the best-performing category, contributing 37.74% of the total quantity sold in 2024.
Landscape products showed an increase in sales, while Indoor plants declined in quantity sold in 2024.
This shift in product demand suggests changing customer preferences or external market factors influencing purchasing decisions.

-How did different countries perform in sales?

Canada, Colombia, and Croatia were among the bottom 10 underperforming countries, showing significant drops in sales.
Several countries that experienced lower sales in 2023 are not included in the 
current year's bottom 10 underperforming countries, indicating positive growth in previously struggling markets. To address the challenges faced by currently underperforming countries in 2024, it is essential to review past strategies and implement targeted strategies and proactive measures. This will help ensure that these countries can make significant progress.
The variations in country-level sales highlight potential issues such as pricing, competition, or market demand differences.

- How did profitability vary across accounts and products?

Not all high-sales accounts were highly profitable, suggesting inefficiencies in pricing or cost structures.
The Account Profitability Segmentation scatter chart revealed that some accounts with strong sales had lower gross profit margins, indicating the need for better pricing strategies.
Products that contributed heavily to total sales volume did not always align with high profit margins.

- What are the key takeaways for sales quantity trends?

Total sales quantity in 2024 decreased compared to 2023, reflecting slower market activity or demand shifts.
Outdoor plants continued to lead sales, but Indoor plants saw a noticeable decline.
Some months showed higher sales activity, emphasizing the need for better demand forecasting and stock management.

- How can GreenLeaf optimize sales and profitability?

Target underperforming regions with strategic marketing efforts to improve sales.
Adjust pricing models to enhance profitability while maintaining sales volumes.
Improve inventory planning based on observed sales trends to prevent overstocking or stockouts.
Continue monitoring profitability per account to ensure that high-sales accounts are also contributing to revenue growth.


## Dashboard
- <a href="https://github.com/GeniDT/GreenLeaf-Performance-Dashboard/blob/main/Performaance%20Dashboard.pbix">View Dashboard</a>

## Recommendations for Stakeholders
-	Optimize Product Strategy: Focus on Outdoor and Landscape products to align with shifting consumer preferences.
-	Market-Specific Adjustments: Address underperforming regions with targeted marketing campaigns and pricing strategies.
-	Inventory Management: Use insights to align stock levels with demand trends, minimizing overstock or shortages.
-	Enhance Data Monitoring: Regularly update and review performance metrics to stay agile in decision-making.

## How to Use the Dashboard
1.	Explore Key Metrics: Navigate through sales, quantity, and gross profit insights.
2.	Apply Filters: Use built-in filters to analyze trends by year, product type, and country.
3.	Make Data-Driven Decisions: Leverage insights to optimize sales strategies and maximize profitability.
   
## Technologies Used
•	Power BI for visualization and interactive reporting.
