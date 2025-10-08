Walmart Sales Analysis — PostgreSQL Project
📘 Overview

This project contains SQL queries to analyze Walmart sales data using PostgreSQL.
It focuses on answering key business questions such as payment trends, customer preferences, and profitability insights.

🗂️ Dataset

The data is stored in a table named walmart_stage, which includes columns such as:

branch

city

category

payment_method

quantity

unit_price

profit_margin

rating

date

time

⚙️ Tools Used

PostgreSQL — Database management and query execution

SQL — Data manipulation and analysis

💡 Business Questions Solved
Q1. Payment Methods & Sales Volume

Find the number of transactions and quantity sold per payment method.

Q2. Highest-Rated Category by Branch

Identify which product category received the highest average rating in each branch.

Q3. Busiest Day by Branch

Determine which day of the week records the most transactions in each branch.

Q4. Quantity Sold per Payment Method

Calculate the total items sold for each payment type.

Q5. Category Ratings by City

Find the average, minimum, and maximum ratings per category across cities.

Q6. Total Profit by Category

Compute total profits per category using:

total_profit = unit_price * quantity * profit_margin

Q7. Sales by Time of Day

Classify transactions into Morning, Afternoon, and Evening based on sale time.

Q8. Most Common Payment Method per Branch

Identify the most preferred payment method for each branch.

📊 Key Insights

Helps Walmart understand branch performance, customer behavior, and profitable product categories.

Enables data-driven decisions on sales strategy and inventory management.

🚀 How to Run

Load the walmart_stage dataset into your PostgreSQL environment.

Open and execute the queries from postgresql.file.sql in a SQL client like pgAdmin or DBeaver.

Review the query results for each business problem.

📁 File Structure
├── postgresql.file.sql   # Main SQL file with queries
├── README.md             # Project documentation

🧠 Author

Nishant Telrandhe
Data Analysis Project using PostgreSQLWalmart Sales Analysis — PostgreSQL Project
📘 Overview

This project contains SQL queries to analyze Walmart sales data using PostgreSQL.
It focuses on answering key business questions such as payment trends, customer preferences, and profitability insights.

🗂️ Dataset

The data is stored in a table named walmart_stage, which includes columns such as:

branch

city

category

payment_method

quantity

unit_price

profit_margin

rating

date

time

⚙️ Tools Used

PostgreSQL — Database management and query execution

SQL — Data manipulation and analysis

💡 Business Questions Solved
Q1. Payment Methods & Sales Volume

Find the number of transactions and quantity sold per payment method.

Q2. Highest-Rated Category by Branch

Identify which product category received the highest average rating in each branch.

Q3. Busiest Day by Branch

Determine which day of the week records the most transactions in each branch.

Q4. Quantity Sold per Payment Method

Calculate the total items sold for each payment type.

Q5. Category Ratings by City

Find the average, minimum, and maximum ratings per category across cities.

Q6. Total Profit by Category

Compute total profits per category using:

total_profit = unit_price * quantity * profit_margin

Q7. Sales by Time of Day

Classify transactions into Morning, Afternoon, and Evening based on sale time.

Q8. Most Common Payment Method per Branch

Identify the most preferred payment method for each branch.

📊 Key Insights

Helps Walmart understand branch performance, customer behavior, and profitable product categories.

Enables data-driven decisions on sales strategy and inventory management.

🚀 How to Run

Load the walmart_stage dataset into your PostgreSQL environment.

Open and execute the queries from postgresql.file.sql in a SQL client like pgAdmin or DBeaver.

Review the query results for each business problem.

📁 File Structure
├── postgresql.file.sql   # Main SQL file with queries
├── README.md             # Project documentation

🧠 Author

Nishant Telrandhe
Data Analysis Project using PostgreSQL
