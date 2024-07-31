# Coffee Sales Dashboard
![cofee_sales](https://github.com/user-attachments/assets/71a63107-871b-4998-9f86-7488007636c9)


## Overview

This dashboard provides an insightful analysis of coffee sales data, created using Microsoft Excel. The dataset includes information on orders, customers, and products, allowing for a comprehensive view of sales performance over time, by region, and by customer.

## Data Sources

### Orders Sheet

| Column Name        | Description                           |
|--------------------|---------------------------------------|
| Order ID           | Unique identifier for each order      |
| Order Date         | Date when the order was placed        |
| Customer ID        | Unique identifier for each customer   |
| Product ID         | Unique identifier for each product    |
| Quantity           | Number of units ordered               |
| Customer Name      | Name of the customer                  |
| Email              | Email address of the customer         |
| Country            | Country where the customer is located |
| Coffee Type        | Type of coffee ordered                |
| Roast Type         | Type of roast (Dark, Light, Medium)   |
| Size               | Package size                          |
| Unit Price         | Price per unit of the product         |
| Sales              | Total sales amount                    |
| Coffee Type Name   | Full name of the coffee type          |
| Roast Type Name    | Full name of the roast type           |
| Loyalty Card       | Indicates if customer has a loyalty card |

### Customers Sheet

| Column Name       | Description                          |
|-------------------|--------------------------------------|
| Customer ID       | Unique identifier for each customer  |
| Customer Name     | Name of the customer                 |
| Email             | Email address of the customer        |
| Phone Number      | Phone number of the customer         |
| Address Line 1    | Street address of the customer       |
| City              | City where the customer is located   |
| Country           | Country where the customer is located|
| Postcode          | Postal code                          |
| Loyalty Card      | Indicates if customer has a loyalty card |

### Products Sheet

| Column Name      | Description                        |
|------------------|------------------------------------|
| Product ID       | Unique identifier for each product |
| Coffee Type      | Type of coffee                     |
| Roast Type       | Type of roast                      |
| Size             | Package size                       |
| Unit Price       | Price per unit of the product      |
| Price per 100g   | Price per 100 grams                |
| Profit           | Profit margin                      |

## Dashboard Components

1. **Total Sales Over Time**
   - **Pivot Table**: Sales by year and month, categorized by Coffee Type Names.
   - **Visualization**: Line chart showing the trend of total sales over time.

2. **Sales by Country**
   - **Pivot Table**: Total sales aggregated by country.
   - **Visualization**: Bar chart highlighting sales performance in different countries.

3. **Top 5 Customers**
   - **Pivot Table**: Sales by customer, sorted to display the top 5 customers.
   - **Visualization**: Bar chart showcasing the top 5 customers based on sales.

## Slicers

1. **Timeline of Order Date**: Allows filtering of data by scrolling through months.
2. **Roast Type Name**: Filters data based on the type of roast (Dark, Light, Medium).
3. **Size**: Filters data based on package size.
4. **Loyalty Card**: Filters data based on whether customers have a loyalty card.

## Key Insights

- **Sales by Country**:
  - The United States leads in sales with $35,639, followed by Ireland with $6,697.

- **Top Customer**:
  - The top customer is Allis Willmore.

- **Sales Trends**:
  - Coffee sales for Excelsa, Liberica, and Arabica are slightly higher in the months of March, April, June, and July.

![image](https://github.com/user-attachments/assets/ce642f99-9fec-4274-87f6-e5da27d750d2)



## Conclusion

This dashboard provides a detailed analysis of coffee sales, highlighting trends over time, regional performance, and key customer insights. The use of slicers enhances the interactivity, allowing users to filter and explore the data effectively.
