# JOINS-PRACTICE

COMPANY: CODTECH IT SOLUTIONS

NAME: Marachu Ganesh

INTERN ID:CT06DL1050

DOMAIN: SQL

DURATION: 6 WEEEKS

MENTOR: NEELA SANTOSH

Perfect. Here's the updated version with the correct title:

---

## JOINS PRACTICE – Task 1

This task involved working with structured data using SQL to simulate a basic relational database system. The objective was to create two related tables, insert sample data into them, and perform various types of JOIN operations to understand how data from multiple tables can be retrieved and combined in different scenarios.

The tools used for this task were MySQL Workbench, MySQL Server, and Visual Studio Code. MySQL Workbench was used to create and manage the database server and schema, while Visual Studio Code served as the code editor where all SQL queries were written and executed. A successful connection between the MySQL database and VS Code was established using appropriate extensions and settings, allowing direct execution of queries from the editor.

To begin the task, two tables were created — one for `Customers` and another for `Orders`. The `Customers` table stores basic information such as the customer's ID, name, and city, while the `Orders` table contains order details including order ID, product name, and the corresponding customer ID. A foreign key constraint was implemented in the `Orders` table to ensure referential integrity, linking each order back to a valid customer.

Once the schema was set up and populated with sample data, the next phase of the task focused on JOIN operations. These operations are central to SQL and relational database systems because they allow combining data from multiple tables based on logical relationships.

An **INNER JOIN** was used to retrieve only those customers who had placed at least one order. This is useful in scenarios where we are interested in only active users or customers who have made transactions. The **LEFT JOIN** query was designed to return all customers regardless of whether they had placed an order or not. This is commonly used in reports that need to include all users along with their associated activity or lack thereof.

The **RIGHT JOIN** reversed the focus — it ensured that all orders were listed, including those that might not have matching customer entries. While this situation shouldn't normally occur if data integrity is maintained, it's a useful technique when cleaning or auditing data. Since MySQL does not natively support FULL OUTER JOIN, this was simulated using a UNION of the LEFT and RIGHT JOIN queries. This approach ensures that all customers and all orders are included in the result, regardless of whether they have corresponding matches in the other table.

Each JOIN operation was tested and its output was reviewed to confirm the correctness of results and to develop a better understanding of how SQL handles relational data. These outputs reflect the underlying relationship between the tables and demonstrate how JOINs can be customized based on the desired output.

This task was extremely valuable in terms of learning and practical exposure. It reinforced the importance of properly designing database schemas and understanding relational integrity. It also helped me gain hands-on experience with SQL syntax and JOIN logic, which is essential for real-world database management and backend development.

In real-world scenarios, such concepts are applied in virtually every database-driven application — whether it's an e-commerce platform showing user orders, a CRM displaying customer interactions, or a financial system linking users to their transaction records. Knowing how to efficiently use JOINs allows developers and analysts to write optimized queries, improve performance, and ensure accurate data reporting.

Overall, this JOINS PRACTICE task gave me a strong foundation in working with relational databases, setting the stage for more advanced operations like aggregations, nested queries, views, and stored procedures in future tasks.


output:
![Image](https://github.com/user-attachments/assets/49370063-2140-44b5-ba50-2238f29efdc3)[](url)
![Image](https://github.com/user-attachments/assets/039bb1e7-8d04-4f4c-9888-b580b9b36e1e)
![Image](https://github.com/user-attachments/assets/039bb1e7-8d04-4f4c-9888-b580b9b36e1e)
