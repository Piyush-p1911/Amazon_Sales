# Amazon_Sales
Amazon Sales Data Analysis
This project focuses on analyzing Amazon sales data using various data tables, including Orders, Returns, and People. The data is processed, transformed, and visualized using Power BI.

Data Tables
1. Orders Table
Contains detailed information about sales transactions, including customer, product, and order-related data.

2. Return Table
Tracks orders that were returned. Includes order ID and the region from which the return occurred.

3. People Table
Contains information about individuals associated with the sales or return data and their respective regions.

Power BI Transformations
Orders Table: Two new columns were added:
Days: Represents the number of days between the order date and the ship date.
Year: Extracted from the order date to track sales by year.
Return Table: A transformation was applied to create a new column:
Returned (1/0): If the order is returned (Yes), the value is 1; otherwise, it is 0.
Usage
Clone or download this repository.
Open the Power BI project file to explore the transformed data.
Use the visualizations and analysis to gain insights into sales, returns, and customer behavior.
