# 🍕 Pizza Sales Data Analysis using SQL

## 📌 Project Overview

This project involves analyzing a pizza sales dataset using **SQL** to uncover valuable business insights that can help drive decisions around sales strategies, customer preferences, and product performance.

The core objective is to simulate a real-world data analysis scenario by using SQL to answer specific business questions. By writing and executing optimized SQL queries, we perform in-depth analysis across different aspects of the pizza business — such as revenue generation, popular products, order trends, and customer behavior.

This project helped solidify my knowledge of:
- SQL joins
- Aggregate functions
- Grouping
- Subqueries
- Window functions
- Data-driven storytelling

---

## 📁 Dataset Description

The project uses four CSV files, which simulate a simplified pizza sales database. Each file represents a key entity in the business.

1. **`orders.csv`**
   - Contains order IDs, order dates, and times when the orders were placed.
   - Represents individual customer orders.

2. **`order_details.csv`**
   - Includes the details of pizzas in each order.
   - Contains the order ID, pizza ID, and quantity ordered.
   - Acts as a bridge table linking orders to pizza items.

3. **`pizzas.csv`**
   - Contains information about each unique pizza such as size and price.
   - Each row has a unique pizza ID.

4. **`pizza_types.csv`**
   - Describes each pizza’s name, category (e.g., Classic, Veggie), and ingredients.
   - Linked to `pizzas.csv` via the pizza type.

These tables can be joined using `pizza_id` and `order_id` to perform comprehensive analysis.

---

## 📊 Key Business Questions & SQL Analysis Performed

The following questions were explored using structured SQL queries:

1. **🧾 Total Number of Orders**
   - Calculated the total number of unique orders placed across the dataset.

2. **💰 Total Revenue Generated**
   - Computed by multiplying the quantity of each pizza sold by its unit price and summing all.

3. **🏷️ Highest-Priced Pizza**
   - Identified the pizza with the highest price across all available sizes.

4. **📏 Most Common Pizza Size**
   - Analyzed which size (S, M, L, XL, XXL) was ordered most frequently.

5. **🔥 Top 5 Most Ordered Pizza Types**
   - Ranked pizzas by total quantity ordered to identify customer favorites.

6. **📦 Category-Wise Quantity Sold**
   - Grouped pizzas by their category (e.g., Classic, Veggie, Chicken) and calculated total units sold.

7. **🕐 Hourly Distribution of Orders**
   - Extracted the hour from the order time to understand peak business hours.

8. **📊 Pizza Distribution by Category**
   - Counted how many distinct pizzas belong to each category.

9. **📅 Average Pizzas Ordered Per Day**
   - Calculated the daily average number of pizzas ordered over the dataset time range.

10. **🏆 Top 3 Revenue-Generating Pizzas**
    - Ranked pizzas based on total revenue contribution and identified the top 3.

11. **📈 Revenue Contribution by Pizza Type**
    - Determined each pizza’s percentage contribution to the total revenue.

12. **📈 Cumulative Revenue Over Time**
    - Tracked revenue growth cumulatively across dates using window functions.

13. **👑 Top 3 Revenue Pizzas per Category**
    - Identified the top 3 revenue-generating pizzas within each pizza category.

---

## 🧠 Skills & Concepts Applied

- **Relational Joins** (INNER JOIN, LEFT JOIN)
- **GROUP BY & Aggregate Functions** (`SUM`, `COUNT`, `AVG`, etc.)
- **Subqueries**
- **Window Functions** (`RANK()`, `ROW_NUMBER()`, `SUM() OVER(...)`)
- **Date & Time Functions** (`DATE()`, `HOUR()` etc.)
- **Data Normalization** through well-structured tables

---

## 🛠️ Tools & Technologies Used

- **SQL (MySQL)**
- **DBMS**: MySQL Workbench / phpMyAdmin
- **Data Format**: CSV files imported into SQL tables
- **Spreadsheet Tools** (optional): For data inspection or query result export

---

## 🚀 How to Run the Project

1. **Set Up MySQL Environment**
   - Use MySQL Workbench, phpMyAdmin, or any other SQL-compatible tool.

2. **Create Tables & Import Data**
   - Convert CSVs into SQL tables using `LOAD DATA INFILE` or import via GUI.

3. **Explore & Execute Queries**
   - Run the prepared SQL queries to generate insights.
   - Optionally export results to Excel or visualize in BI tools.

4. **Customize & Extend**
   - Modify queries to explore other metrics such as seasonal trends, customer segmentation, or profit margins.

---

## ✅ Sample Output Examples (Optional)

> You can insert screenshots or result samples here showing outputs of a few major queries.

---

## 📚 Key Learnings

This project allowed me to:
- Understand business problem-solving through SQL
- Strengthen data manipulation and analysis techniques
- Apply real-world database concepts using structured, normalized data
- Present insights in a format useful for stakeholders



