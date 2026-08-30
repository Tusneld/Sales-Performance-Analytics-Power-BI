# Retail Store Sales Dashboard
---
![Power BI Dashboard](https://github.com/Tusneld/Sales-Performance-Analytics-Power-BI/blob/ade5e3211950b00a0efc53b5e301bb235a5fb8f3/Power%20BI%20V2%20Dashboard.PNG)
---
## Table of Contents

- [Overview](#overview)
- [Business Questions](#business-questions)
- [Key Metrics](#key-metrics)
- [Tech Stack](#tech-stack)
- [Steps Taken](#steps-taken)
- [Recommendations](#recommendations)
- [Lessons Learned](#lessons-learned)

## Overview

This project involves building a professional, interactive **Retail Store Sales Dashboard** from scratch in *Power BI*. The objective is to provide actionable insights into store performance through visual summaries and trend analysis.

## Business Questions

This dashboard was designed to address the following key business inquiries:

- **Performance Overview:** What are the total sales, total profit, and the overall profit ratio of the retail store?
- **Geographic Insights:** Which cities and countries are driving the most sales?
- **Product Performance:** Which categories and subcategories are the most profitable?
- **Sales Trends:** How has the store's performance evolved over time, and how does profit compare to sales trends?

## Key Metrics

The dashboard tracks several performance indicators to help stakeholders make data-driven decisions:

- **Total Sales:** Aggregate revenue generated.
- **Total Profit:** Absolute profit value.
- **Profit Ratio:** The percentage of profit relative to total sales.
- **Top 5 City Performance:** Benchmarking the highest-performing cities by sales and profit.

## Tech Stack

- **Primary Tool:** Power BI Desktop
- **Data Sources:** Excel Workbooks (.xlsx)
- **Data Modeling:** Power Query (for data transformation and cleaning) and Relationship Modeling (Star Schema design)
- **Visualizations:** Customizing standard visuals, conditional formatting, and integrating Azure Map visuals
- **Advanced Functionality:** DAX (Data Analysis Expressions) for custom metrics, Bookmarks and Selection Pane for interactive toggling, and Slicers for filtering

## Steps Taken

1. **Data Preparation:** Imported raw Excel files, used Power Query to promote headers, and cleaned data formats.
2. **Data Modeling:** Established a star schema by connecting the core orders table to people, returns, and date calendar tables.
3. **Metric Calculation:** Created DAX measures for core KPIs: *Total Sales*, *Total Profit*, and *Profit Ratio*.
4. **Dashboard Design:** Built the layout using a background template, configured high-level summary cards, and developed interactive tables and charts.
5. **Advanced Interactivity:** Implemented a "toggle" feature using bookmarks and buttons to allow users to switch between Sales and Profit trends on a single line chart.

## Recommendations

Based on the analysis provided by the dashboard, I will recommend the retail store to consider the following strategic steps:

- **Resource Allocation:** Focus marketing and inventory efforts on the top-performing geographic locations (cities) and high-profit subcategories.
- **Profitability Optimization:** Investigate the underlying causes of low profit ratios in specific categories and look for opportunities to reduce costs or adjust pricing strategies.
- **Trend Monitoring:** Use the toggleable sales and profit trend lines to identify seasonal patterns and adjust operational staffing or inventory levels accordingly during peak months.

## Lessons Learned

- **User Experience (UX):** Designing for the end-user requires intuitive navigation; utilizing bookmarks creates a clean interface without cluttering the screen with too many visuals.
- **Data Integrity:** Investing time in proper modeling (Star Schema) and data transformation is critical to prevent future calculation errors and performance issues.
- **Dashboard Storytelling:** Conditional formatting and consistent color palettes are essential for drawing attention to specific insights, such as high-performing vs. low-performing regions.
- **Iterative Refinement:** Building a professional dashboard is an iterative process that benefits from grouping objects and simplifying visual complexity to improve readability.
