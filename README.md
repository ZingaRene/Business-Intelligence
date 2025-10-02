# Business-Intelligence

## Overview

Welcome to the **PowerBI-Projects** repository! This repository is an organized collection of hands-on projects developed during the **Microsoft Power BI for Business Intelligence and Data Science** course. The course focuses on essential skills for data analysis, visualization, and business intelligence using Power BI, with an emphasis on interactive reports, dashboards, and data modeling.

The main directory (`/`) contains several subdirectories, each dedicated to a hands-on lab (Lab) in the course. Each subdirectory includes:
- `.pbix` files (Power BI reports ready to open and edit).
- Original datasets (CSV, Excel, or SQL dumps).
- Specific README.md files with reproduction instructions, insights, and lessons learned.
- Screenshots or images of dashboards for quick viewing.

These projects are based on applying real-world BI and Data Science concepts, such as data cleansing, DAX, semantic modeling, and advanced visualizations, with a focus on global business scenarios, financial analysis, and KPIs.

**Prerequisites**: Basic Excel/SQL knowledge; the DSA course is ideal for Power BI beginners.

## Hands-On Projects

Here is a detailed description of each hands-on project (Labs), organized by course sequence. Each one addresses a specific aspect of Power BI, using real or simulated data for business scenarios.

### Project 1: Global Sales Analytics Dashboard
- **Description**: Development of an interactive dashboard for international sales analysis, including filters by region, product, and period. Uses CSV data import, creation of DAX measures for totals and YoY (Year-over-Year) growth, and visualizations such as maps and stacked bar charts.
- **Skills Practiced**: Data connection, relational modeling, slicers, and tooltips.
- **Data Used**: Global sales set (sales, quantities, revenue by country).
- **Results**: Dashboard with sales performance KPIs, allowing drill-down by continent.
- **Subdirectory**: `/proj1_vendas_globais/`
![Global Sales Analysis](Global_Sales_analisys.png)

### Project 2: Sales, Cost, Profit Margin, and KPI Dashboard
- **Description**: Creation of a report focused on operational finances, calculating profit margins, variable costs, and KPIs such as ROI (Return on Investment) and conversion rate. Includes line charts for monthly trends and cards for key metrics.
- **Skills Practiced**: Advanced DAX formulas (SUMX, DIVIDE), table relationships, and conditional formatting.
- **Data Used**: Sales, cost, and inventory tables (Excel).
- **Results**: Integrated visualization for pricing decisions and inventory control.
- **Subdirectory**: `/proj2_vendas_custo_kpi/`

### Project 3: Accounting Data Analysis - Balance Sheet
- **Description**: Balance sheet analysis focusing on assets, liabilities, and equity. The project generates annual comparative reports using calculated columns for financial ratios (e.g., current liquidity).
- **Skills Practiced**: Importing financial data from Excel, creating hierarchies and waterfall charts for variations.
- **Data Used**: Company balance sheets (multiple years).
- **Results**: Dashboard for auditing and strategic planning, with alerts for imbalances.
- **Subdirectory**: `/proj3_balanco_patrimonial/`

### Project 4: Marketing and Campaign Analysis
- **Description**: Dashboard for marketing campaign ROI, tracking clicks, conversions, and cost per acquisition (CPA). Includes channel segmentation (email, social media) and sales funnel.
- **Skills Practiced**: Integration with web data (via Power Query), time intelligence metrics (e.g., SAMEPERIODLASTYEAR), and multiple pages.
- **Data Used**: Campaign logs (simulated Google Analytics).
- **Results**: Report optimized for digital marketing budget allocation.
- **Subdirectory**: `/proj4_analise_marketing/`

### Project 5: Demand Forecasting with Power BI
- **Description**: Simple predictive model for forecasting product demand, using time series and forecast visualizations. Integrates historical data for simulations.
- **Skills Practiced**: Trend analysis, line charts with automatic forecasting, and export to PowerPoint.
- **Data Used**: Seasonal sales series (monthly).
- **Results**: Supply chain dashboard, reducing excess inventory.
- **Subdirectory**: `/proj5_previsao_demanda/`

## License
Feel free to clone, fork, or contribute improvements to the dashboards (e.g., new visualizations). All projects are open-source under the MIT license.

For questions, open an issue in this repo. Thanks for visiting!

---

*Last updated: October 2, 2025*
