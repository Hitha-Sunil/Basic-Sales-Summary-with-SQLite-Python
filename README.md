🛒 Basic Sales Summary with SQLite & Python
📌 Overview
This project demonstrates how to connect Python with a SQLite database, run simple SQL queries, and generate a basic sales summary.
The results are displayed both as a table and a bar chart using Pandas and Matplotlib.

⚙ Tools Used
Python (Anaconda / Jupyter Notebook)

SQLite3 (built into Python)

Pandas (for data handling)

Matplotlib (for visualization)
📂 Dataset
A small SQLite database (sales_data.db) is created with a single table:

sales

id (Primary Key)

product (Text)

quantity (Integer)

price (Real)

Sample records include Laptop, Mobile, and Tablet sales.

📊 Results
SQL Query Output (example):

product	total_qty	revenue
Laptop	8	575000.0
Mobile	16	332000.0
Tablet	12	184000.0
➡ Laptop generated the highest revenue, followed by Mobile and Tablet.

Visualization
A bar chart is plotted to show Revenue by Product.

🚀 How to Run
Clone this repository

Open the Jupyter Notebook (.ipynb) or Python script (.py)

Run cells to:

Create the SQLite database

Insert sample data

Query and display results

Plot revenue chart

📌 Deliverables
✅ sales_data.db (SQLite database)

✅ Python script / Jupyter Notebook

✅ Sales summary (table + bar chart)
