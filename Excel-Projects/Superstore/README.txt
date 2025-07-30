README - Superstore Sales Data Analysis

📁 Project Overview
This project involves cleaning, preprocessing, and analyzing the Superstore dataset in Excel. The goal is to extract meaningful business insights using data visualization and summary statistics.

🧹 Data Cleaning & Preprocessing
1. Date Format Standardization:
   - Converted Order Date and Ship Date to standard date format (yyyy-mm-dd).
   - Sorted the dataset in order based on Latest Date.

2. Shipping Delay Calculation:
   - Created a new column "Delay" = Ship Date - Order Date.

3. Postal Code Separation:
   - Split Postal Code from State for clarity and usability.

4. Text Formatting:
   - Applied TRIM and PROPER functions to clean City and State columns:
     - Removed leading/trailing spaces.
     - Converted names to title case (e.g., "new york" → "New York").

📊 Charts & Visual Elements Used
- Column Chart: Used to show total profit by state and segment.
- Bar Chart: Displayed top products by sales and loss-making products.
- Pie Chart: Represented regional profit distribution.
- Combo Chart: Combined sales and profit data for comparative visualization.
- Slicer: Enabled interactive filtering by region, segment, and ship mode.
- Theme & Styling:
  - Applied consistent color theme.
  - Customized fonts, column widths, and chart elements for clarity.

📈 Key Findings
1. Profit Distribution by Region:
   - West region recorded the highest total profit.

2. Product Performance:
   - Fast-Moving Product: Parasonic (average sales)
   - Slow-Moving Product: SanDisk Cruzer 8 GB USB

3. Top 5 Products by Sales:
   - Identified using sorted bar chart (products with highest total sales).

4. Top 5 Loss-Making Products:
   - Products with highest total loss (negative profit).

5. Top 5 States by Profit:
   - California ranked #1 in total profit.

6. High Discount, Low Profit Product:
   - Xerox 1969 – high discount rate, significantly low/negative profit.

7. Profit by Segment:
   - Consumer segment contributed the most to total profit.

8. Shipping Delay Insights:
   - West region has the maximum average shipping delay.
   - Second Class shipping mode had the highest average delay.

9. Negative Profit Products:
   - Highlighted products consistently producing a net loss.

📌 Conclusion
This analysis provides a comprehensive overview of key sales, profit, and shipping trends. It can guide business decisions such as:
- Reducing discount on loss-making products.
- Re-evaluating shipping strategies in high-delay regions.
- Focusing on top-selling items and profitable segments.
