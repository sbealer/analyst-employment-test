###Description
Using a free relational database management system of your choice (SQLite, MySQL, SQL Server Express, PostgreSQL, etc.) load the comma seperated files found in the data_files directory of this project into individual database tables. Once you have done so, complete the tasks below. **Many users of this test choose SQLiteStudio to load this data and perform the required exercises. SQLiteStudio allows you to easily create a database and import csv as tables.**

####WARNING:Please ensure that data types are properly assigned to each column regardless of which RDBMS you choose (e.g. salary as a float, ids as integers, etc). If data types are not set correctly, aggregate functions such as 'SUM, 'MAX, etc may not work correctly.

To submit your answers, create a Google doc with sections for each task. For each section, provide the answer AND the SQL used (if applicable) to determine that answer.

###Tasks

1. Which RDMS did you use to complete this test? Why did you use this product?

2. What is the name of the employee with the highest salary? Use SQL to determine and provide with answer.

3. In which year did the company hire the most employees? Use SQL to determine and provide with answer.

4. In which year/month were the most products sold? How much simple revenue (sum of product_price for all items purchased that month) did the company earn?

5. How many orders were placed in July 2015? Use SQL to determine and provide with answer.

6. Provide the `customer_id` of the customer who has the greatest number of purchases.

7. Provide a column chart showing revenue per year with X axis being year, Y axis being revenue.

8. A bar chart showing employee_id and salary sorted by salary least to greatest.

9. A bar chart showing employee_id and total hours worked on all projects sorted least to greatest.

###Extra credit:

10. Join the `projects` table to the `employees` table to determine the name of the employee who has worked on the most projects. Use SQL to determine and provide with answer.
11. Join the `employees`, `salary` and `projects` tables together to determine salary of the employee who has worked on the fewest projects.
12. Which category has generated the most revenue of all time?
13. Provide a chart of your choice showing something from the dataset that you found interesting.

