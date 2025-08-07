# Excel Retail Sales Analysis & Performance Report

## Objective
The primary goal of this project was to analyze a retail sales dataset to identify key performance metrics and uncover insights related to product profitability and sales performance. Using Microsoft Excel, I transformed the raw data into an actionable report, moving from basic data cleaning to advanced formula-based analysis and interactive dashboarding with PivotTables.

## Dataset
This analysis was performed on a fictional sales dataset for a bike store. The dataset contains thousands of rows of transactional data, including information on order dates, customer demographics (age, gender, country), product details (category, sub-category), and order financials (unit cost, unit price, profit, revenue).

## Tools & Skills
* **Microsoft Excel**
* **Data Transformation:**
    * Calculated new columns using formulas (`Profit / Revenue`).
    * Categorized data using nested `IF` statements to create performance labels ("High," "Standard," "Low").
    * Calculated conditional bonuses (`IF` statement with multiplication).
* **Data Summarization & Analysis:**
    * Created **PivotTables** to aggregate data and identify key trends.
    * Used all four PivotTable areas (**Rows, Columns, Values, Filters**) to conduct multi-dimensional analysis.
* **Interactive Dashboarding:**
    * Utilized **Slicers** to create a user-friendly and interactive filtering experience.
    * Generated **PivotCharts** that dynamically update based on slicer selection, providing clear data visualizations.

## Analysis & Key Findings
This project involved a multi-step analysis process:

1.  **Data Enrichment:** I started by enhancing the raw dataset. I created a `Profit_Margin` column to assess the profitability of each individual sale. This was crucial for moving beyond simple revenue numbers and understanding true performance.

2.  **Conditional Categorization:** Using a nested `IF` statement, I created a `Performance_Label` column. This automatically categorized every sale as "High," "Standard," or "Low" profit, which allowed for quick segmentation and analysis of the most and least effective transactions.

3.  **Actionable Insights:** To make the analysis actionable, I created a `Sales_Bonus` column. This formula automatically calculated a 5% bonus on the revenue of any sale that was labeled "High," demonstrating how analysis can directly inform business operations like incentive programs.

4.  **Interactive Reporting:** The enriched data was then used to build a PivotTable dashboard. By combining PivotTables, PivotCharts, and Slicers, I created a dynamic report where a user could easily filter sales data by `Country` and instantly see updated charts and summaries for different product categories and customer genders.

## Final Report
The final interactive report, including all calculated columns, the PivotTable, Slicer, and PivotChart, can be viewed in the **`Sales_Performance_Analysis.xlsx`** file included in this repository.
