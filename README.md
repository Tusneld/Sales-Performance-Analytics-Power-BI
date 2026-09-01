# Retail Store Sales Dashboard

An end-to-end Power BI project that transforms raw retail transaction data into a polished, interactive dashboard — giving stakeholders a clear, visual way to track performance and make data-informed decisions.

---
![Power BI Dashboard](https://github.com/Tusneld/Sales-Performance-Analytics-Power-BI/blob/ade5e3211950b00a0efc53b5e301bb235a5fb8f3/Power%20BI%20V2%20Dashboard.PNG)
---
# Retail Store Sales Schema
---
![Star Schema](https://github.com/Tusneld/Sales-Performance-Analytics-Power-BI/blob/fcab01055941e2665ca128fff985cbbb4bebd351/Star%20Schema.PNG)
---

## Table of Contents

- [Overview](#overview)
- [Business Questions](#business-questions)
- [Key Metrics](#key-metrics)
- [Tech Stack](#tech-stack)
- [Data Model](#data-model)
- [Steps Taken](#steps-taken)
- [How to Use This Dashboard](#how-to-use-this-dashboard)
- [Recommendations](#recommendations)
- [Lessons Learned](#lessons-learned)

## Overview

This project involves building a professional, interactive **Retail Store Sales Dashboard** from scratch in Power BI. The objective is to provide actionable insights into store performance through visual summaries and trend analysis — turning raw sales data into a tool that supports faster, more confident business decisions.

## Business Questions

This dashboard was designed to address the following key business inquiries:

- **Performance Overview:** What are the total sales, total profit, and the overall profit ratio of the retail store?
- **Geographic Insights:** Which cities and countries are driving the most sales?
- **Product Performance:** Which categories and subcategories are the most profitable?
- **Sales Trends:** How has the store's performance evolved over time, and how does profit compare to sales trends?

## Key Metrics

The dashboard tracks the following performance indicators to help stakeholders make data-driven decisions:

- **Total Sales:** Aggregate revenue generated.
- **Total Profit:** Absolute profit value.
- **Profit Ratio:** The percentage of profit relative to total sales.
- **Top 5 City Performance:** Benchmarking the highest-performing cities by sales and profit.

## Tech Stack

- **Primary Tool:** Power BI Desktop
- **Data Sources:** Excel Workbooks (.xlsx)
- **Data Modeling:** Power Query (data transformation and cleaning) and Relationship Modeling (Star Schema design)
- **Visualizations:** Custom-styled standard visuals, conditional formatting, and Azure Map visuals
- **Advanced Functionality:** DAX (Data Analysis Expressions) for custom metrics, Bookmarks and the Selection Pane for interactive toggling, and Slicers for filtering

## Data Model

The dataset is organized using a star schema, with a central **Orders** fact table connected to three supporting dimension tables: **People**, **Returns**, and a **Date Calendar** table. This structure keeps the model efficient and ensures calculations stay accurate as filters and slicers are applied.

# Retail Store Sales Schema
---
https://github.com/Tusneld/Sales-Performance-Analytics-Power-BI/blob/fcab01055941e2665ca128fff985cbbb4bebd351/Star%20Schema.PNG
---

## Steps Taken

1. **Data Preparation:** Imported raw Excel files, used Power Query to promote headers, and cleaned data formats.
2. **Data Modeling:** Established a star schema by connecting the core Orders table to the People, Returns, and Date Calendar tables.
3. **Metric Calculation:** Created DAX measures for core KPIs: *Total Sales*, *Total Profit*, and *Profit Ratio*.
4. **Dashboard Design:** Built the layout using a background template, configured high-level summary cards, and developed interactive tables and charts.
5. **Advanced Interactivity:** Implemented a toggle feature using bookmarks and buttons to allow users to switch between Sales and Profit trends on a single line chart.

## How to Use This Dashboard

No prior Power BI or data experience is needed to explore this dashboard. Here's how to get started:

1. **Get Power BI Desktop (free).** If you don't already have it, download [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop) from Microsoft — it's free and works on Windows.
2. **Download the project files.** From this repository, download the `.pbix` dashboard file (and the source Excel data, if you'd like to see the raw dataset behind it).
3. **Open the `.pbix` file.** Double-click it, or open it from within Power BI Desktop via *File > Open*. The dashboard will load with all visuals and data already built in — no setup required.
4. **Explore with the filters and slicers.** Use the dropdowns and buttons at the top of the report to filter by year, month, or other categories. The dashboard will update instantly.
5. **Try the Sales/Profit toggle.** Click the toggle buttons above the trend chart to switch between viewing the Sales trend and the Profit trend over time.
6. **Hover for details.** Hover your mouse over any chart, bar, or map marker to see exact figures in a pop-up tooltip.

*Tip: If you just want to view the dashboard without installing anything, ask for a published Power BI Service link or a PDF/image export — either can be shared for quick viewing on any device.*

## Recommendations

Based on the analysis provided by the dashboard, the following strategic steps are recommended:

- **Resource Allocation:** Focus marketing and inventory efforts on the top-performing geographic locations (cities) and high-profit subcategories.
- **Profitability Optimization:** Investigate the underlying causes of low profit ratios in specific categories and look for opportunities to reduce costs or adjust pricing strategies.
- **Trend Monitoring:** Use the toggleable sales and profit trend lines to identify seasonal patterns and adjust operational staffing or inventory levels accordingly during peak months.

## Lessons Learned

- **User Experience (UX):** Designing for the end-user requires intuitive navigation; utilizing bookmarks creates a clean interface without cluttering the screen with too many visuals.
- **Data Integrity:** Investing time in proper modeling (Star Schema) and data transformation is critical to prevent future calculation errors and performance issues.
- **Dashboard Storytelling:** Conditional formatting and consistent color palettes are essential for drawing attention to specific insights, such as high-performing vs. low-performing regions.
- **Iterative Refinement:** Building a professional dashboard is an iterative process that benefits from grouping objects and simplifying visual complexity to improve readability.
