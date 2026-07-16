# 🛒 Zepto SQL Data Analysis Project

A real-world SQL data analysis project based on a Zepto product dataset. This project focuses on solving practical business problems using **MySQL** by analyzing product pricing, discounts, inventory, and category-wise performance.

---

## 📌 Project Overview

The objective of this project is to perform exploratory data analysis (EDA) on a Zepto product dataset using SQL. The project demonstrates how SQL can be used to answer business questions and generate actionable insights from retail data.

---

## 🛠️ Tech Stack

* **Database:** MySQL 8.0
* **Language:** SQL
* **Dataset:** Zepto Product Dataset (CSV)
* **Tools:** MySQL Workbench, GitHub

---

## 📂 Dataset Information

The dataset contains product-level information, including:

| Column                   | Description                                         |
| ------------------------ | --------------------------------------------------- |
| `sku_id`                 | Unique product identifier                           |
| `category`               | Product category                                    |
| `name`                   | Product name                                        |
| `mrp`                    | Maximum Retail Price                                |
| `discountPercent`        | Discount percentage offered                         |
| `availableQuantity`      | Available stock quantity                            |
| `discountedSellingPrice` | Selling price after discount                        |
| `weightInGms`            | Product weight (grams)                              |
| `outOfStock`             | Stock availability (1 = Out of Stock, 0 = In Stock) |
| `quantity`               | Number of product units                             |

---

# 📊 Business Problems Solved

### 1. Find the top 10 best-value products based on discount percentage.

### 2. Identify products with high MRP that are out of stock.

### 3. Calculate estimated revenue for each category.

### 4. Find products where:

* MRP > ₹500
* Discount < 10%

### 5. Identify the top 5 categories offering the highest average discount.

### 6. Calculate price per gram for products weighing more than 100g.

### 7. Categorize products into:

* Low
* Medium
* Bulk

### 8. Calculate total inventory weight for each category.

---

# 📚 SQL Concepts Used

* SELECT
* WHERE
* ORDER BY
* LIMIT
* DISTINCT
* GROUP BY
* HAVING
* Aggregate Functions (`SUM`, `AVG`, `COUNT`, `MIN`, `MAX`)
* CASE Statements
* Aliases
* Arithmetic Operations
* Data Cleaning
* Filtering & Sorting

---

# 📈 Sample SQL Query

```sql
SELECT name,
       discountPercent
FROM zepto
ORDER BY discountPercent DESC
LIMIT 10;
```

---

# 📁 Project Structure

```text
Zepto-SQL-Data-Analysis/
│
├── Dataset/
│   └── zepto_v2.csv
│
├── SQL Queries/
│   ├── table_creation.sql
│   ├── data_cleaning.sql
│   ├── business_queries.sql
│
├── README.md
```

---

# 🚀 Key Insights

* Identified products with the highest discounts.
* Analyzed high-priced products that are unavailable.
* Estimated category-wise revenue.
* Compared discount strategies across categories.
* Calculated price efficiency using price per gram.
* Segmented products based on quantity.
* Evaluated inventory distribution by category.

---

# 🎯 Learning Outcomes

Through this project, I strengthened my understanding of:

* Writing optimized SQL queries
* Data cleaning in SQL
* Business-oriented data analysis
* Aggregate functions and grouping
* Conditional logic using `CASE`
* Solving real-world retail analytics problems

---

# 📸 Output Preview

> You can add screenshots of your SQL query results here.

Example:

```text
images/
├── top_discount_products.png
├── revenue_by_category.png
├── inventory_weight.png
```

---

# 👨‍💻 Author

**Mridul Sharma**

* Aspiring Data Analyst
* Skilled in SQL, Python, Excel, Power BI, and Tableau
* Passionate about solving real-world business problems using data

---

## ⭐ If you found this project useful, consider giving it a star!
