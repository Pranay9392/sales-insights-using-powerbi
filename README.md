# Sales Insights Data Analytics Project

![Power BI Dashboard Screenshot](dashboard_screenshot.png) <!-- Add your actual screenshot file name -->

## Project Overview
This Power BI project analyzes sales data from a MySQL database, providing actionable insights through interactive visualizations. The dashboard tracks key performance indicators (KPIs), revenue trends, and sales patterns across different markets.

## Key Features
- **Data Integration**: Direct connection to MySQL database
- **Data Transformation**: Cleaned and normalized sales data
- **Interactive Dashboards**: 5+ visualizations with cross-filtering
- **Key Metrics**: Revenue, Sales Quantity, Profit Margins by region/product
- **Time Intelligence**: Year-over-year and month-by-month analysis

## Technical Components
- **Data Source**: MySQL relational database
- **Tools Used**: 
  - Power BI (Desktop version)
  - MySQL Workbench
  - Power Query for ETL

## Repository Contents
- `sales_analysis.pbix` - Power BI project file
- `db_dump.sql` - MySQL database backup
- `dashboard_screenshot.png` - Dashboard preview
- `data_model.png` - Relationship diagram (optional)

## Setup Instructions

### 1. Database Setup
1. Install MySQL Server using [this guide](https://www.youtube.com/watch?v=WuBcTJnIuzo)
2. Import the database:
   ```bash
   mysql -u root -p < db_dump.sql
