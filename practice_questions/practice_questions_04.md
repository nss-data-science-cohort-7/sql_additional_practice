## Practice Questions 4

1. We have seen how a CASE statement can be used to fill in the shipper information. Now, let’s use a more efficient way to accomplish the same outcome. Write a query which selects all columns from the orders table and adds the companyname column from the shippers table.
2. Write a query which returns the orderdate, companyname, city, and country for each order in the orders table.
3. Write a query which finds all rows of the order table for orders from customers located in the UK. Then modify your query to show the average freight for these orders.
4. Write a query which returns two columns, the first containing employeename and the second containing the number of orders associated with that employee. Hint: you'll need to do a JOIN and a GROUP BY to get this answer.
5. Write a query which returns the average unitprice for each category of products by category name. Include only products which are not discontinued in this calculation.

Challenge Questions

6. Write a query which returns two columns, the first containing country and the second containing the number of orders to companies located in that country. Hint: you'll need to do a JOIN and a GROUP BY to get this answer. Bonus: Have your result set show only countries that have at least 50 orders.
7. Write a query to find all orderids for orders including at least one product in the "Produce" category. Hint: You’ll need to use multiple JOINS to get this result.
8. Write a query which calculates the total revenue per year. Then write another query to find the total revenue per month and year.
