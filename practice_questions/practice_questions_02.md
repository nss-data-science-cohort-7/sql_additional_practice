## Practice Questions 2

1. Using the SUBSTRING function, find all customers whose contacttitle starts with "Sales"
2. Write a query which returns all customers located in the UK. In the country column of your output, display "United Kingdom" instead of "UK".
3. Find all products whose productname is less than 10 characters long.
4. Using the categories table, write a query which will return one column which contains the category name and description separated by a colon. For example, the row for beverages should look like "Beverages: Soft drinks, coffees, teas, beers, and ales".
5. Find all orders with an orderdate in December.
6. Find all orders with an orderdate in December of 2014.
7. Write a query which finds all orders which were ordered in one year and shipped the next year. For example, orderid 10380, having an orderdate of 2013-12-12 and a shippeddate of 2014-01-16 is one such order.
8. Write a query that returns for each product in the products table the productid, productname, quantityperunit, and the unitprice in both USD and CAD. Use 1.35 CAD / 1 USD to convert. Currently, the unitprice column is in USD.
9. Write a query which returns, for each order, all of the columns in the orders table along with the shipper name. Use a CASE clause to fill in the shipper name. Note that shipperid 1 corresponds to Speedy Express, shipperid 2 corresponds to United Package, and shipperid 3 corresponds to Federal Shipping.