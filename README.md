# Product_Analysis_Report
This is a sales report of product by countries

## Table Outlay

|Date|	Customer ID|	Customer Age|	Age Group|	Customer Gender|	Country|	State|	Product Category|	Sub Category|	Product|	Frame Size|	Order Quantity|	Unit Cost|	Unit Price|	Cost|	Revenue|	Profit|
|------|------|------|------|------|-------|------|-------|-------|------|--------|-------|-------|---------|--------|-------|--------|
|26/11/2013|	11019|	19|	Youth (<25)|	M	|Canada|	British| Columbia|	Accessories|	Bike Racks|	Hitch Rack| - 4-Bike|		8|	45|	120|	360	|950	|590|
|26/11/2015|	11019|	19|	Youth (<25)|	M|	Canada|	British |Columbia|	Accessories|	Bike Racks|	Hitch Rack| - 4-Bike	|	8	|45|	120	|360	|950	|590|
|23/03/2014|	11039|	49|	Adults (35-64)|	M	|Australia|	New South Wales|	Accessories|	Bike Racks	|Hitch Rack| - 4-Bike	|	23|	45	|120|	1035	|2401|	1366|

Note: To see all table content visit kaggle.com for accessories file:


---
##  Accessories_sales_analysis
_This report gives us an insight about Sales data in the United States._

__This also contains dasboard__

--- 
## Project Overview
> This project bring to view the analytical report of sales data to uncover insights on sales distribution by various attributes such as bike, clothes and accessories. Using the power bi, I explored metrics like total sales by product, country and region. The average income of buyers, gender distribution, and overall revenue was also explored.  This analysis helps to understand the key factors driving car sales in the USA and identifies patterns across different segments.

---

## Data Source: 
- Data Source:
+ www.kaggle.com
  
## Tools Used
### Power BI: 
      1. For creating interactive visualizations
      2. For Dashboard Creation 
      3. For visuals that present data insights in a user-friendly format

### SQL 
> #### Task
```sql
1. Write a query to retrieve Customer above 50 years
2. Write SQL Query to retrieve customers who purchased above 1000 dollars
3. Write query to retrieve all accessories of bikes
4. Retrieve all customers in Canada
5. Retrieve all product category and profit and rename product category to Products

```

## Data Overview
_The dataset includes the following columns:_

> __CustomerID: Unique identifier for each car sold.__
> +	Age Group: Exploring the age ranges
> +	Country: Geographic location where the product was sold.
> -	Product Category: Exploring the three products in the dataset
> -	Profit: Income flow profit
> -	Gender: Gender of the buyer.
> -	Revenue: Revenue generated from each sale.

## Data Visualization
[To view the power bi dashboard, click here](https://ibb.co/9MmFX94)

## Dashboard Visuals

![Uploading Screenshot (286).png…]()

## SQL QUERIES
```sql
SELECT * FROM accessories
WHERE customer age > 50;
```

```sql
SELECT * FROM accessories
WHERE revenue >= 1000;
```

```sql
SELECT * FROM accessories
WHERE Product Category LIKE '%bike%'
```

```sql
SELECT * FROM accessories
WHERE country = 'Canada';
```

```sql
SELECT product_category AS Products, profit FROM accessories; 
```

