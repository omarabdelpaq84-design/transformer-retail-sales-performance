# Transformer Company: Retail Sales & Profitability Analysis 📈📦

## Project Overview
This project provides a detailed evaluation of the sales operations and financial health of the "Transformer Company," a retail entity operating across multiple regions. By analyzing over 5,000 orders, the project identifies high-performing product categories, regional sales leaders, and critical metrics such as delivery duration and profit margins.

## Project Workflow
The repository is structured to demonstrate professional data integration and analytical reporting:

1.  **Sales Data (`Orders`):** The core dataset containing granular transaction details, including customer segments (Consumer, Corporate, Home Office), product categories (Technology, Furniture, Office Supplies), and financial metrics (Sales, Profit, Discount, COGS).
2.  **Returns Tracking (`Return`):** A supplemental dataset used to identify returned orders, allowing for "Net Sales" calculations and identifying potential quality or logistics issues.
3.  **Regional Management (`People`):** Mapping regional sales performance to specific managers (e.g., Anna Andreadi for the West region).
4.  **Strategic Metrics (`Measures`):** High-level business KPIs and aggregations, including:
    * **Executive Summary:** Total Sales (~$2.3M), Total Profit (~$286K), and a total of 5,009 orders from 793 unique customers.
    * **Product Performance:** Identifying top-selling sub-categories like Phones ($330K) and Chairs ($328K).
    * **Regional Distribution:** Performance breakdown across the West ($725K), East ($678K), Central ($501K), and South ($391K) regions.
    * **Geographic Hotspots:** City-level analysis highlighting New York City and Los Angeles as primary revenue drivers.

## Key Insights Analyzed
- **Profitability vs. Volume:** Analyzing which categories (e.g., Technology) yield the highest profit margins compared to sales volume.
- **Logistics Efficiency:** Measuring the 'Delivery Duration' (days between Order Date and Ship Date) to assess supply chain performance.
- **Discount Impact:** Investigating how discount values affect total profit and whether high discounts correlate with higher return rates.
- **Customer Segmentation:** Evaluating the purchasing power and frequency of different customer segments.

## Tools Used
- **Microsoft Excel:** For data modeling, Power Query (to join Orders and Returns), and complex pivot table analysis.
- **Financial Analytics:** Calculating COGS (Cost of Goods Sold), Profit Margins, and regional growth metrics.

## How to Explore
- Check `Orders.csv` for the primary transactional data including delivery timelines and product details.
- Refer to `Measures.csv` for the consolidated financial performance by region and category.

---
*Developed as part of a Retail Business Intelligence portfolio.*
