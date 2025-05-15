# Ecommerce SQL Data Analysis Task 3

## Overview
This repo contains the SQL code and dataset used to complete **Task 3: SQL for Data Analysis** — focusing on importing, querying, and analyzing an ecommerce sales dataset using MySQL.

---

## Dataset

- `ecommerce_data.csv` — Cleaned ecommerce sales data with columns:  
  `User_ID,Product_ID,Category,Price,Discount,Final_Price,Payment_Method,Purchase_Date`
  The dataset was cleaned to remove trailing commas and properly format datetime values to ensure successful import.

---

## SQL Code is attached with Repo

The SQL scripts include:

- Creating the `sales_data` table with appropriate column types.
- Importing the cleaned CSV dataset using `LOAD DATA INFILE`.
- Sample queries demonstrating:
  - Data selection (`SELECT`, `LIMIT`)
  - Aggregations (`SUM`, `AVG`)
  - Grouping (`GROUP BY`)
  - Filtering (`WHERE`)
  - Sorting (`ORDER BY`)
