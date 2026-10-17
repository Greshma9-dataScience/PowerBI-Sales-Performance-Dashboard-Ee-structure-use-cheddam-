DAX Measures — Sales Performance Analysis

1. Revenue (Calculated Column)

Revenue = Sales[Quantity] * Sales[Price]

Calculates revenue for each order.

2. Total Revenue (Measure)

Total Revenue = SUM(Sales[Revenue])

Calculates total revenue from all orders.

3. Total Orders (Measure)

Total Orders = DISTINCTCOUNT(Sales[OrderID])

Counts the unique orders.

4. Total Quantity (Measure)

Total Quantity = SUM(Sales[Quantity])

Calculates the total quantity of products sold.

Expected Results

- Total Revenue: ₹1,56,000
- Total Orders: 6
- Total Quantity: 16
