## Practice Questions 3

1. Use COUNT(*) to find the total number of rows in the orders table. Then use COUNT on the shippeddate column of the orders table. Why do you get different numbers?
2. Using the order_details table, find the total number of units of "Chef Anton's Gumbo Mix" that have been sold. Hint: this item's productid is 5. Name the output column "total_units".
3. What is the average quantity for orders of Chef Anton's Gumbo Mix?
4. Using the orders table, write a query which returns a row for each customerid which shows the number of orders for each customerid.
5. What productid has the largest total number of units sold?
6. If an order includes more than one type of product, it will have multiple rows in the order_details table. Write a query which returns the orderids for orders which involve only one productid. 

Challenge Questions

7. Write a query using the products table which returns a table showing the list of categoryids and the average of the discontinued column per categoryid. How can we interpret this average value?
8. Write a query which finds the total revenue (after discount) associated with each productid. Which product id has the highest total revenue?
9. Which month of 2014 had the most number of sales?
