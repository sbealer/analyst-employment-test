####Using a free relational database management system of your choice (SQLite, MySQL, SQL Server Express, PostgreSQL, etc.) load the comma seperated files found in the data_files directory of this project into individual database tables. Once you have done so, complete the tasks below. **Many users of this test choose SQLiteStudio to load this data and perform the required exercises. SQLiteStudio allows you to easily create a database and import csv as tables.**

To submit your answers, create a Google doc with sections for each task (1, 2-i, 2-ii, etc). For each section, provide the answer AND the SQL used (if applicable) to determine that answer.

###Tasks
1. **Which RDMS did you use to complete this test? Why did you use this product?**

2. **Using the employees and salary tables:**
  1. What is the name of the employee with the highest salary? Use SQL to determine and provide with answer.
  2. In which year did the company hire the most employees? Use SQL to determine and provide with answer.
  3. **Extra credit:**
    1. Join the projects table to the employees table to determine the name of the employee who has worked on the most projects. Use SQL to determine and provide with answer.
    2. Join the employees, salary and projects tables together to determine salary of the employee who has worked on the fewest projects. 
    
3. **Using the orders, order_products, product and category tables:**
  1. In which year/month were the most products sold? How much simple revenue (sum of product_price for all items purchased that month) did the company earn?
  2. How many orders were placed in July 2015? Use SQL to determine and provide with answer.
  3. Provide the customer_id of the customer who has the greatest number of purchases. 
  4. **Extra credit:**
  	1. Which category has generated the most revenue of all time?
  
4. **Provide screenshots of the following graphs (you can use Google spreadsheets to create the graphs):**
  1. A column chart showing revenue per year with X axis being year, Y axis being revenue.
  2. A bar chart showing employee_id and salary sorted by salary least to greatest.
  3. A bar chart showing employee_id and total hours worked on all projects sorted least to greatest.
  4. **Extra credit:**
  	1. Provide a chart of your choice showing something from the dataset that you found interesting.