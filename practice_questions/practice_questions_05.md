## Practice Questions 5

1. Write a query to find the customerid for all orders that had an orderdate in May of 2014. Then convert this to a subquery using the IN keyword in order to find all company names for companies that had an order in May of 2014.
2. Write a query which finds the average freight value across all orders. Then convert this into a subquery to find all orders that had an above-average freight cost.
3. Subqueries can also be used inside of other clauses. In this exercise, you can see how to use a subquery in FROM.
    - Write a query which finds all orders from February of 2014.
    - Use the query you wrote in part a as a subquery that you join with the employees table in order to add the employeename to the result set. Make sure that all employees appear, not just those that had a sale in that month.
    - Finally, modify your query to count the number of sales by employeename for February of 2014. Your result table should display 0 for employees that had no sales.
4. Write a query which returns all rows from the products table with a new column showing the average unitprice for each product's category.
5. Write a query which returns all columns from the products table along with a rank column which ranks each product based on its unitprice in descending order.

Challenge Questions

6. Modify your query for question 5 so that the ranks are assigned within categories. Hint: You'll need to add a PARTITION BY to your OVER expression.
7. Subqueries can also be used inside of other clauses. In this exercise, you can see how to use a subquery in SELECT.
    - Write a query which finds the total number of orders.
    - Write a query which finds the total number of orders by shipperid.
    - Add your query from part a to your SELECT clause so that your query shows the number of orders by shipperid and the total number of orders.
    - Finally, add a column showing the percentage of total orders for each shipper. You'll need to use the subquery again as part of this calculation.
