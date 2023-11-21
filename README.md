# Home_sales

## Project Description
In this project, SparkSQL was employed to determine key metrics about home sales data. The utilization of SparkSQL involved various 
operations such as creating temporary views, partitioning the data, caching and uncaching a temporary table, and verifying that the 
table has been uncached.

## Data
Visit Home Sales dataset to see dataset used in this project.

## Analysis
Query 1: Average price for a four-bedroom house sold for each year

![image](https://github.com/Devang63/Home_sales/assets/128569122/2736125a-6435-47ca-9d65-f4a6b30c7898)


Query 2: Average price of a home for each year it was built that has three bedrooms and three bathrooms

![image](https://github.com/Devang63/Home_sales/assets/128569122/d1ef15b0-35aa-4db6-ade8-c07ce35d4a8b)


Query 3: Average price of a home for each year that has three bedrooms, three bathrooms, 
two floors, and is greater than or equal to 2,000 square feet

![image](https://github.com/Devang63/Home_sales/assets/128569122/314fe3b1-8372-4f88-96ee-3ac361131530)


Query 4: View rating for homes costing more than or equal to $350,000 group by view

![image](https://github.com/Devang63/Home_sales/assets/128569122/d1f4f160-0df2-47f6-94c2-aea78c57cca3)


Compare Run Times on Query 4

1. Uncache Runtime: 0.8774685859680176 seconds
2. Cached Runtime: 0.5805220603942871 seconds
3. Runtime with the parquet DataFrame: 0.48909735679626465 seconds
