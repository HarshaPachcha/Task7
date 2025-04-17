# Task7
Basic Sales Summary with SQLite & Python

## Objective
Extract basic sales information from an SQLite database using SQL queries inside Python and visualize the result.

## Tools Used
- Python (sqlite3, pandas, matplotlib)
- SQLite (sales_data.db)

## Key Steps
- Connected to SQLite using `sqlite3.connect()`
- Queried sales data using SQL (`GROUP BY product`)
- Loaded results into pandas
- Displayed a bar chart of revenue by product

## Output
- Printed total quantity and revenue
- Generated a bar chart saved as `sales_chart.png`
