Task 7 – Basic Sales Summary using SQLite and Python

Objective:
To create a small SQLite database of sales records and generate a summary using SQL within Python. The results are displayed using both `print` statements and a simple bar chart.

Tools & Libraries Used:

- Google Colab – Cloud-based Python environment
- SQLite3 – Built-in Python library for database management
- Pandas – For handling SQL results in table format
- Matplotlib – For visualizing revenue with a bar chart

Dataset Description:

We created a small in-memory SQLite table named `sales` with the following fields:

| Field | Type |
|-------|------|
| id | INTEGER (Primary Key) |
| product | TEXT |
| quantity | INTEGER |
| price | REAL |

Sample data included entries for Pens, Notebooks, Pencils, and Erasers with different quantities and prices.

---

Steps Followed:

1. Created a `sales` table in an SQLite database.
2. Inserted multiple rows of product sales.
3. Ran a SQL query to calculate:
   - Total quantity sold per product.
   - Total revenue per product (`quantity * price`).
4. Used **Pandas** to load and print the results as a DataFrame.
5. Used **Matplotlib** to create a bar chart of revenue by product.

Output Screenshot:

![image](https://github.com/user-attachments/assets/62b0b9d7-591b-4732-bdb0-65aa29202e00)


How to Run This:

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run all cells — no external file is needed since the database is generated in-memory.
3. The printed table and bar chart will appear below the code cell.

Key Concepts Practiced:

- Connecting Python to a database
- Writing SQL inside Python
- Aggregating data using `GROUP BY`
- Performing calculations inside SQL queries
- Loading SQL query results into a Pandas DataFrame
- Creating a basic bar chart with Matplotlib
