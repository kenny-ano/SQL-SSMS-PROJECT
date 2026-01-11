# SQL-SSMS-PROJECT
# Retail Sales Analysis – SQL Project

## Author
**Adeyemi Adeshola Kehinde**

---

## Project Overview

This project focuses on analyzing a retail sales dataset using SQL.  
The objective is to import, clean, and query sales data to generate meaningful business insights.

SQL Server and SQL Server Management Studio (SSMS) were used to perform data cleaning, aggregation, and analytical queries.

---

## Tools Used

- SQL Server  
- SQL Server Management Studio (SSMS)  
- CSV Dataset  

---

## Dataset Description

The dataset contains retail transaction records including:

- Customer demographics  
- Product categories  
- Sales amount and quantity  
- Transaction dates and times  

---

## Step 1: Importing the Dataset

The dataset was imported into SQL Server using the Import Flat File Wizard in SSMS.

Steps:
1. Connected to the database in SSMS  
2. Right-clicked the database → Tasks → Import Flat File  
3. Selected the CSV file and verified column data types  
4. Saved the table as `RetailSales`

---

## Step 2: Data Cleaning

Data quality checks were performed to identify missing values across key columns.

Records with NULL values in critical fields were removed to ensure accuracy and consistency of analysis.

---

## Step 3: SQL Queries and Analysis

The following analyses were carried out:

- Sales made on a specific date  
- Category based sales with quantity filters  
- Total sales per product category  
- Average customer age by category  
- High value transactions  
- Transaction counts by gender and category  
- Monthly average sales  
- Best selling month per year  
- Top 5 customers by total sales  
- Unique customer count per category  
- Order distribution by shift (Morning, Afternoon, Evening)

---

## Project Screenshots

### Dataset Import in SSMS
![Dataset Import](images/dataset_import.png)

### Data Cleaning Query
![Data Cleaning](images/data_cleaning.png)

### Sales Analysis Query Results
![Sales Analysis](images/sales_analysis.png)

---

## Key Skills Demonstrated

- SQL data cleaning  
- Aggregate functions  
- Subqueries and CTEs  
- Date and time analysis  
- Business insight generation  

---

## Conclusion

The dataset was successfully imported, cleaned, and analyzed using SQL.  
The queries provided valuable insights into sales trends, customer behavior, and transaction patterns.
