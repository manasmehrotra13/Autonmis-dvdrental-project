# DVD Rental: Market Insights and Performance Analysis

Case study from my data analyst internship at **Autonmis** (early 2025), on the public PostgreSQL "dvdrental" sample database.

## The data
15 tables (films, actors, categories, customers, addresses, stores, staff, rentals, payments and more), about 65,000 rows.

## What I did
- Joined the 15 tables into 3 analysis tables: actors and films; staff with their payments and rentals; customers with their addresses.
- Wrote about 16 SQL queries:
  - KPIs: total revenue (about $61,300) and revenue per customer (about $102)
  - customer lifetime value with CTEs
  - the top films, actors and customers
  - staff performance and monthly trends
  - each category's share of revenue with window functions
  - rental duration with `EXTRACT(EPOCH ...)`
- Built a dashboard on the Autonmis platform and wrote up the case study.

## Tools
PostgreSQL, SQL (joins, CTEs, window functions, date functions), the Autonmis platform.

## Files
- `dvdrental datasets.zip`: the data
- `DVD Rental Market Insights and Performance Analysis.pdf`: the write-up
- `dvdrental dashboard.pdf`: the dashboard
- two images
