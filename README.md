# Financial Performance Analysis: Wage Spend vs Premier League Performance

## Question
Does spending more on wages lead to better league performance in the Premier League?

## Data
- Club financial data (revenue and staff costs) from Companies House accounts, collected and cleaned in Excel
- Match results from the [DataHub Premier League dataset], 2021-22 to 2024-25
- Scope: 13 clubs across four seasons
  
## Method
1. Collected and cleaned club finance data in Excel
2. Built a relational SQLite database and used SQL (joins, aggregation, views) to calculate league tables and cost per point
3. Built an interactive Power BI dashboard: scatter plot, cost-per-point comparison and trend analysis

## Findings
The relationship between wage spend and points varied between seasons, with R² ranging from 0.22 to 0.83. 

## Limitations
Small club sample, accounts ended at different dates, group companies v individual.

## Dashboard
<img width="591" height="330" alt="image" src="https://github.com/user-attachments/assets/2e4ffdbc-3999-48bf-abf8-d4a23cce4f84" />


## Tools
SQLite, Navicat, SQL, Excel (Power Query), Power BI

## Files
- `[filename].sql`: queries used
- `[filename]`: cleaned data
