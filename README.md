# Sales Market Intelligence & Forecasting - Power BI

Built with AI/BI to solve a real business problem: 70% revenue concentration in single customer type and 95% sales from 3 countries - market risk requiring predictive forecasting.

This Power BI Sales Performance Dashboard analyzes $37.5M sales, 5M quantity, and 3.23M average monthly sales - similar architecture to African Intelligence Engine goal of converting raw data into searchable intelligence and decision-support.

## Problem Statement
Raw sales data was fragmented across regions, customer types, and time periods. No unified view of market concentration, geographic dependency, or seasonality. Needed system to detect relationships, trends, and anomalies for business intelligence.

## Architecture

### 1. Structured Knowledge Graph
- **Nations:** Geographic map visual - US, UK, Germany, Australia, France - Sum of Sales by Country
- **Corporations & Sectors:** Customer Type breakdown - Novelty Shop $14,728 (70% concentration), Boutique, Department Store, Corporate
- **Markets & Economic Indicators:** Year (2020-2023), Month, Quantity, Average Monthly Sales, Total Orders

### 2. Predictive & Analytical Framework
- **Market Forecasting Foundation:** Sales by Quantity line chart by Month - shows seasonality, trend detection, Q4 peaks
- **Business Intelligence:** Year/Month detailed table - Jan $799k, Feb $1.1M - time series for forecasting
- **Anomaly Detection:** 70% Novelty Shop dependency = concentration risk, geographic concentration = market anomaly
- **Data Value Chain:** Raw data (10k+ rows) → Information (KPIs: 37.5M sales) → Insight (70% concentration risk) → Intelligence (diversification needed) → Decision

### 3. Data Pipeline for AI/ML
- **ETL:** Power Query - Extracted, cleaned, and transformed raw data
- **Data Modeling:** Relationships between Sales, Customer, Geography, Date tables
- **Feature Engineering:** DAX Measures - Sum of Sales, Sum of Quantity, Average Monthly Sales, Total Orders, Calculated columns
- **Data Validation & QA:** Timeline controls, handling empty periods, data quality checks

## Dashboard Visuals

- **KPIs:** Sum of Sales 37.5M, Sum of Quantity 5M, Average Monthly Sales 3.23M, Total Orders
- **Slicers:** Year (2020, 2021, 2022, 2023) - interactive filtering changes all visuals
- **Customer Type:** Bar chart - Novelty Shop $14,728 leads, shows 70% concentration
- **Sales by Quantity:** Line chart by Month - trend analysis for forecasting
- **Geographic Map:** Sum of Sales by Country - US, UK, Germany concentration
- **Detailed Table:** Year/Month breakdown for granular market analysis

## Tech Stack

- **BI & Analytics:** Power BI (Power Query, DAX, Data Modeling, Relationships, KPI Cards, Map Visuals)
- **Data Engineering:** SQL (Aggregation, JOINs, GROUP BY, Data Cleaning), Excel (PivotTables, Slicers)
- **Analytical:** Predictive Analytics, Market Forecasting, Trend Detection, Anomaly Detection, Business Intelligence
- **Product:** Data Pipelines, Data Validation, Feature Engineering, Data Readiness

## Key Insights

1. **Concentration Risk:** 70% revenue from Novelty Shops - single customer type dependency
2. **Geographic Risk:** 95% sales from US/UK/Germany - needs market diversification
3. **Seasonality:** Sales by Quantity shows Q4 peaks - predictive for inventory and staffing
4. **Recommendation:** Diversify customer types and expand to underperforming regions - same logic as African market intelligence for expansion decisions

## Use Case for African Intelligence Engine

Same architecture needed for African markets:
- Raw African business data (fragmented across regions/sectors) → Power BI pipeline → Geographic map of African nations → Customer type analysis → Market concentration detection → Decision-support for market entry and risk management

This dashboard proves ability to build systems that detect relationships, trends, and anomalies in market data

## Files

- Power BI Dashboard: $37.5M Sales Performance Dashboard with Geographic Map and Customer Type analysis (Available via Releases for large .pbix file)
- Dataset: Enterprise sales dataset (2020-2023) - cleaned via Power Query, ~10k+ rows
- Demo Video: Shows Year slicer filtering 2020-2023, Customer Type interaction, Map tooltips

## How to Run

1. Download .pbix file from Releases (or request via email)
2. Open in Power BI Desktop
3. Use Year slicer (2020-2023) to see sales update from $37.5M to $41.4M
4. Click Customer Type Novelty Shop $14,728 to see concentration risk
5. Hover on Map to see Sum of Sales by Country

## Author

Aroh Chidimma - AI/ML Engineer
Python, SQL, RAG, LLMs, Power BI, Market Intelligence
GitHub: github.com/chidimma-aroh
Live Timely Prototype: https://timely-me2eozpj.manus.space/
Location: Lagos, Nigeria | Open to Remote
