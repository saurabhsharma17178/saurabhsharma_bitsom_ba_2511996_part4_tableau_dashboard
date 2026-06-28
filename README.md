# Task 1: Connect and Inspect Data

## Objective

The objective of this task is to connect the provided sales dataset to Tableau and inspect the available fields before creating visualizations. The dataset was reviewed to understand its structure, data types, and business relevance.

---

# Dataset Information

- **Dataset Name:** dashboard_sales_data.xlsx
- **Total Records:** 4,200
- **Total Columns:** 20
- **Source:** Assignment Dataset

---

# Date Fields

The following fields were identified as date fields:

| Field Name | Data Type | Purpose |
|------------|-----------|---------|
| order_date | Date | Order placement date |
| ship_date | Date | Product shipping date |

---

# Geographic Fields

The following fields represent geographical information:

| Field Name | Purpose |
|------------|----------|
| region | Sales region |
| state | Customer state |
| city | Customer city |

---

# Categorical Fields

These fields are used for grouping and comparison.

| Field Name |
|------------|
| customer_segment |
| category |
| sub_category |
| product_name |
| ship_mode |
| campaign_channel |

---

# Numerical Measures

These fields are continuous business measures used for calculations and analysis.

| Field Name | Description |
|------------|-------------|
| sales | Total sales amount |
| profit | Profit earned |
| quantity | Number of items sold |
| discount | Discount percentage |
| delivery_days | Days required for delivery |
| customer_rating | Customer satisfaction rating |

---

# Binary / Flag Field

The dataset contains one binary field.

| Field Name | Values |
|------------|--------|
| return_flag | Yes / No |

---

# Identifier Fields

These fields uniquely identify business records.

| Field Name |
|------------|
| order_id |
| customer_id |

---

# Assumptions

The following assumptions were made during data inspection:

- The dataset is complete and ready for analysis.
- Order Date and Ship Date are recognized as Date fields.
- Sales, Profit, Discount, Quantity, Delivery Days, and Customer Rating are treated as numerical measures.
- Region, State, and City are considered geographical dimensions.
- Return Flag is treated as a binary categorical field.
- Order ID and Customer ID are unique identifiers.
- No missing values or duplicate records were modified during this task.
- No calculated fields or data transformations were created during data inspection.

---

# Summary

The dataset contains sufficient information to analyze sales performance, profitability, customer behavior, regional performance, shipping efficiency, discount impact, and product returns. The inspected data structure will be used to build an executive dashboard in the following tasks.