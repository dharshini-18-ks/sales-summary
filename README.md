# sales-summary

1. Database and Data Setup

* A small SQLite database file named **sales_data.db** is created.
* It contains a single table, sales, populated with sample transactional records (Product, Quantity, Price).

2. SQL Query Execution

* A complex SQL query is executed using pd.read_sql_query() to perform a Group By aggregation.
* The query calculates the total quantity sold (total_qty) and the total revenue (revenue) for each product.

3. Analysis and Output

The script generates the following key outputs:

* *Console Output:* Prints the overall *Total Quantity Sold* and *Total Revenue*.
* *DataFrame:* Displays the product-wise summary table.

4. Visualization

* A simple bar chart, **sales_bar_chart.png**, is generated using Matplotlib.
* The chart visualizes the *Total Revenue* across different products.
