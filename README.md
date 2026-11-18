# Financial Performance Analysis: Wage Spend vs Premier League Performance

## Question
Does spending more on wages lead to better league performance in the Premier League?

## Data
- Club financial data (revenue and staff costs) from Companies House accounts, collected and cleaned in Excel
- Match results from the [DataHub Premier League dataset], 2021-22 to 2024-25
- Scope: 13 clubs across four seasons [add any clubs you excluded and why]

## Method
1. Collected and cleaned club finance data in Excel
2. Built a relational SQLite database and used SQL (joins, aggregation, views) to calculate league tables and cost per point
3. Built an interactive Power BI dashboard: scatter plot, cost-per-point comparison and trend analysis

## Findings
The relationship between wage spend and points varied between seasons, with R² ranging from 0.22 to 0.83. [Add 1-2 sentences on what you found, e.g. which clubs got the most or fewest points per £ of wages.]

## Limitations
[Add 1-2 honest points, e.g. small sample of clubs, wages are only one factor, accounts cover different year-ends.]

## Dashboard
[Add screenshots here]

## Tools
SQLite, Navicat, SQL, Excel (Power Query), Power BI

## Files
- `[filename].sql`: queries used
- `[filename]`: cleaned data
