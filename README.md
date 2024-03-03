#### Database-Works
This database task involves the creation of a relational database named "Ahmad" with three tables: "Salesman," "customer," and "Orders." The tables are designed to store information related to salesmen, customers, and orders. Here's a summary of the database schema and the provided data:
# Database Schema:
1. **Salesman Table:**
   - Columns: salesman_Id (Primary Key), Name, city, commission

2. **Customer Table:**
   - Columns: customer_Id (Primary Key), cust_name, city, grade, salesman_Id (Foreign Key referencing Salesman)

3. **Orders Table:**
   - Columns: ord_no (Primary Key), purch_amount, ord_date, customer_id (Foreign Key referencing customer), salesman_id (Foreign Key referencing Salesman)

# Provided Data:
The INSERT statements add data to the respective tables.

# Queries:
1. **Join Salesman and customer:**
   - Display the names and cities of salesmen and customers where the city of the salesman matches the city of the customer.

2. **Filter Orders by Amount:**
   - Retrieve order details (order number, purchase amount, customer name, and city) where the purchase amount is between 200 and 500.

3. **Join Customer and Salesman for Commission:**
   - Display customer names, cities, salesman names, and commissions where the salesman_Id in the customer table matches the salesman_Id in the Salesman table.

4. **Filtered Join with Commission Criteria:**
   - Display customer names, cities, salesman names, and commissions where the commission is greater than 0.12.

5. **Join Customer and Salesman with Additional Columns:**
   - Display customer names, cities, grades, salesman names, and cities where the salesman_Id in the customer table matches the salesman_Id in the Salesman table.

6. **Filter Customers by Grade:**
   - Display salesman names, customer cities, and customer names where the grade in the customer table is less than 300.

7. **Right Join Salesman and customer:**
   - Retrieve salesman Id and names using a right join between Salesman and customer tables, ordered by Salesman names in ascending order.

### Description:
The provided SQL queries aim to extract meaningful information from the database. They involve joins between the "Salesman," "customer," and "Orders" tables to connect relevant data. The queries cover a range of scenarios, such as filtering orders by purchase amount, displaying customer and salesman details, and considering specific criteria like commission values and customer grades. Each query serves a particular analytical purpose within the context of the database schema and the provided data.
