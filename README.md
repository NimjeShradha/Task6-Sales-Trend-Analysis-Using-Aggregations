# Task6-Sales-Trend-Analysis-Using-Aggregations
Sales Trend Analysis Using Aggregations
Used PostgreSQL script for Creating Sales Trend Analysis using Aggregation
1) Created a Database as Online_Sales
2) Created Table with Invoice_ID, Branch, City, Product_line, Unit_price, Quantity, Tax_5, Total_price, Order_date, Order_time, Payment_method, costs, gross_income, Rating
3) Assigned Datatypes for each Column Data of Table
4) Imported Data Using COPY Command. 
5) Used EXTRACT To Extract the Order_Date Column's Year & Month
6) Used COUNT & DISTINCT to have the Uniques Values in Invoice ID To Count as Total_Orders
7) Used SUM Aggregation to calculate  Total_Revenue of the Orders.
8) Used GROUP BY for Year & Month to Group the Monthly & Yearly Sales & ORDER BY for to ensuring Results in Orderly Manner
9) Lastly Used LIMIT to Show the Top Sales Revenue.
