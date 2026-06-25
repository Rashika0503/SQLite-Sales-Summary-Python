# Task 7: Basic Sales Summary Using SQLite and Python

## 📌 Project Overview
This project demonstrates how to use SQLite with Python to create a small sales database, execute SQL queries, analyze sales data, and visualize revenue using a bar chart. It is a beginner-friendly project that introduces the integration of SQL and Python for basic data analysis.

---

## 🎯 Objective
- Create a SQLite database using Python.
- Create a sales table and insert sample sales data.
- Execute SQL queries to calculate total quantity sold and total revenue.
- Load SQL query results into a Pandas DataFrame.
- Visualize revenue by product using Matplotlib.

---

## 🛠️ Tools & Technologies
- Python
- SQLite (sqlite3)
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📂 Project Files

```
Task7_Sales_Summary.ipynb   # Jupyter Notebook
sales_data.db              # SQLite Database
sales_chart.png            # Revenue Bar Chart
README.md                  # Project Documentation
```

---

## 📊 Dataset
A small sample sales dataset was created manually with the following columns:

- Product
- Quantity
- Price

---

## 🗄️ SQL Query Used

```sql
SELECT
    product,
    SUM(quantity) AS total_qty,
    SUM(quantity * price) AS revenue
FROM sales
GROUP BY product;
```

---

## 📈 Project Workflow

1. Import required libraries.
2. Create a SQLite database.
3. Create the sales table.
4. Insert sample sales records.
5. Execute SQL queries using Python.
6. Load query results into a Pandas DataFrame.
7. Display the sales summary.
8. Generate a revenue bar chart.
9. Save the visualization as a PNG image.
10. Close the database connection.

---

## 📌 Output

The project provides:

- Sales summary by product
- Total quantity sold
- Total revenue generated
- Revenue visualization using a bar chart

---

## 🚀 Learning Outcomes

- SQLite database creation using Python
- Executing SQL queries in Python
- Using Pandas with SQL databases
- Data aggregation using SQL
- Basic data visualization with Matplotlib

---

## 👩‍💻 Author

**Rashika Diwekar**

Aspiring Data Analyst | Python | SQL | Excel | Power BI
