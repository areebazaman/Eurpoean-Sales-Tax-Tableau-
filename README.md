# European Sales Performance Dashboard — Tableau


Project Type: Business Intelligence / Data Visualisation
Tool Used: Tableau Desktop (Sample – EU Superstore dataset, ~10,000 orders)
Overview
This project is an interactive Tableau dashboard built to analyse and communicate European retail sales performance. Using the EU Superstore dataset, the workbook consolidates sales, profit, and product data into a single executive-facing dashboard, enabling quick identification of top-performing regions, products, and time-based trends.
Dashboard Components
The workbook is structured across four analytical sheets, all feeding into one unified dashboard:
KPI Summary — A high-level scorecard displaying total Sales and Profit, filterable by Country/Region and Order Date, giving decision-makers an instant snapshot of overall performance.
Sales by Country (Map View) — A choropleth geographic map encoding sales volume by colour intensity across European countries, allowing instant visual identification of strongest and weakest markets.
Sales by Month (Trend Line) — A time-series view tracking sales across months and years, revealing seasonality patterns, growth trajectories, and any notable dips or peaks in revenue.
Sales by Product (Bar Chart with Highlighting) — A sub-category level breakdown of sales with a calculated field — Above Avg Sales — that dynamically colour-codes products performing above or below the window average, helping prioritise high-impact product lines.
Key Technical Feature
A custom table calculation (SUM([Sales]) >= WINDOW_AVG(SUM([Sales]))) was implemented to flag above-average performers, demonstrating knowledge of Tableau's level-of-detail and window functions beyond basic drag-and-drop.
What This Demonstrates
Proficiency in Tableau for end-to-end dashboard development — data connection, sheet design, calculated fields, geographic mapping, time-series analysis, and dashboard composition — with a focus on clarity and business relevance.
