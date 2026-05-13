# Grant Financial Dashboard

## Overview
This project presents an interactive Power BI dashboard designed to monitor federal grant financial performance. The dashboard provides visibility into grant balances, expenditures, available funds, burn rates, deadline risks, and drawdown activity.

## Business Problem
Program managers need timely and accurate insight into grant spending, remaining balances, and compliance risks. This dashboard helps identify grants that may require attention before deadlines or funding issues occur.

## Dataset
The dashboard uses grant and financial reporting data, including:
- Award numbers
- Grantee names
- Grant status
- Grant balances
- Expenditures
- Available funds
- Period of Performance end dates
- Statutory deadline dates
- Drawdown activity

## Tools and Technologies
- Power BI
- Excel
- DAX
- Data Modeling
- Data Visualization

## Methodology
1. Imported grant and financial data into Power BI.
2. Reviewed and cleaned key data fields.
3. Created relationships between grant and financial tables.
4. Built DAX measures for balances, expenditures, available funds, drawdown status, and burn rates.
5. Created risk indicators for POP end dates and statutory deadlines.
6. Designed dashboard visuals, slicers, KPI cards, and summary charts.
7. Tested visuals and filters for accuracy.

## Key Dashboard Features
- Total number of awards
- Number of active awards
- Number of inactive awards
- Available funds by award number
- Awards with no drawdowns
- Fully drawn awards
- Portfolio burn rate
- POP ending soon flag
- Statutory deadline risk flag
- Interactive slicers and filters

## Results and Insights
- The dashboard helps identify grants with high remaining balances.
- Risk flags help users quickly locate awards needing attention.
- Slicers allow users to filter by award status, deadline risk, and drawdown activity.
- KPI cards provide a quick executive-level summary of portfolio performance.

## How to Use This Project
1. Open the Power BI `.pbix` file in Power BI Desktop.
2. Refresh the data connections if needed.
3. Review the dashboard pages.
4. Use slicers to filter awards by status, deadline risk, or drawdown activity.
5. Review KPI cards and visuals for grant performance insights.

## Project Structure
```text
grant-dashboard/
│── README.md
│── grant_dashboard.pbix
│── data/
│── images/
│── measures/
