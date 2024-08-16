# SQLite Database Project

This project involves creating and querying an SQLite database using SQLite Studio. The database, named **"sample"**, includes a table called **"test_data"** with various product information. The assignment covers the following tasks:

1. **Database Creation**: 
   - Create an SQLite database named **"sample"**.

2. **Table Creation and Data Loading**: 
   - Set up a table named **"test_data"** and populate it with sample product data including the following fields:
     - `Order_ID`
     - `Product_Name`
     - `Category`
     - `Quantity`
     - `Price`

3. **SQL Queries**: 
   - Write and execute SQL queries to:
     - Retrieve `Product_Name` and `Price` for products where the `Category` is 'Electronics'.
     - Compute the average price of products in the 'Apparel' category.
     - Select all fields of products where the `Price` is less than 200.
     - Retrieve `Order_ID` and `Product_Name` of products where the `Quantity` is equal to 1.
     - Compute the total revenue (`Price * Quantity`) for each category.
