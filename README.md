# 🛒 Zepto Sales Data Analysis (SQL Project)

This project focuses on analyzing **Real Zepto's sales dataset** using SQL to extract meaningful business insights.  
The goal is to understand sales trends, stock patterns, and product performance through structured queries.

## 📌 Project Objective

- To perform data analysis on Zepto sales data and answer real-world business questions using SQL.
- Perfom **Exploratory Data Analysis (EDA)** to explore product categories, availability, and pricing inconsistencies.
- Implement **Data Cleaning** to handle null values, removes invalid entries, and converts pricing from paise to rupees.
- **Solve business-driven** queries to extract useful insights around pricing, inventory stock availability and more.

##  🔧 Tools & Technologies Used

- **Language:** SQL  
- **Database:** PostgreSQL / pgAdmin  
- **Query tool:** pgAdmin
- **Dataset Source:** Kaggle (CSV format)  

## 📂 Dataset Information

The dataset contains the following columns(10) such as:

- **sku_id:** Unique identifier (Primary key)
- **name:** Product name as appears on the app
- **category:** Different categories of products like.. Beverage, Snacks, Fruits, etc.
- **mrp:** Max. retail price (originally in paise, converted to rupees)
- **discountPercent:** Discount applied on MRP
- **discountedSellingPrice:** Final price after discount
- **availableQuantity:** Availability of Units in Inventory
- **weightInGms:** Products weight in grams
- **outOfStock:** Boolean flag indicating stock availability ( true = stock, false = out of stock)
- **quantity:** Total no. of units per pacakage

## 🔍 Key Analysis Performed

Some important business questions solved in this project:

1. Identified the **Top 10 best-value products** based on highest discount percentage  
2. Found products with **high MRP but currently out of stock**  
3. Calculated **estimated revenue for each product category**  
4. Retrieved products where **MRP > ₹500 and discount < 10%**  
5. Identified the **Top 5 categories** offering the highest average discount  
6. Computed **price per gram** for products above 100g and ranked by best value  
7. Grouped products into **Low, Medium, and Bulk** categories based on quantity  
8. Calculated the **total inventory weight per category**

## 📁 Project Files

- `zepto_project.sql` → SQL queries used for analysis  
- `README.md` → Project documentation  


##  How to Use This Project

1. Import the dataset into PostgreSQL
2. Open pgAdmin Query Tool
3. Run the SQL queries from the `.sql` file
4. Analyze the results

## 📈 Skills Demonstrated

- SQL querying  
- Data analysis
- Data cleaning 
- Business problem solving  
- Data interpretation  

## 🙋‍♂️ Author

**Lavkush**  
Aspiring Data Analyst

[LinkedIn](https://www.linkedin.com/in/lavkush2005kumar)

---
These analysis help understand pricing strategy, discount patterns, inventory distribution, and category-wise business performance.


## ⭐ If you found this helpful, consider giving it a star
