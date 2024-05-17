# Electronics Retail Store Project

## Introduction

This project utilizes an Excel dataset from an electronics retail store for in-depth analysis and insights. The main goal is to understand the store's performance and customer behavior, which can help in strategic decision-making.

## Dataset Description

### Sales
- **Order Number**: Unique ID for each order.
- **Line Item**: Identifies individual products purchased as part of an order.
- **Order Date**: Date the order was placed.
- **Delivery Date**: Date the order was delivered.
- **CustomerKey**: Unique key identifying which customer placed the order.
- **StoreKey**: Unique key identifying which store processed the order.
- **ProductKey**: Unique key identifying which product was purchased.
- **Quantity**: Number of items purchased.
- **Currency Code**: Currency used to process the order.

### Customers
- **CustomerKey**: Primary key to identify customers.
- **Gender**: Customer gender.
- **Name**: Customer full name.
- **City**: Customer city.
- **State Code**: Customer state (abbreviated).
- **State**: Customer state (full).
- **Zip Code**: Customer zip code.
- **Country**: Customer country.
- **Continent**: Customer continent.
- **Birthday**: Customer date of birth.

### Products
- **ProductKey**: Primary key to identify products.
- **Product Name**: Product name.
- **Brand**: Product brand.
- **Color**: Product color.
- **Unit Cost USD**: Cost to produce the product in USD.
- **Unit Price USD**: Product list price in USD.
- **SubcategoryKey**: Key to identify product subcategories.
- **Subcategory**: Product subcategory name.
- **CategoryKey**: Key to identify product categories.
- **Category**: Product category name.

### Stores
- **StoreKey**: Primary key to identify stores.
- **Country**: Store country.
- **State**: Store state.
- **Square Meters**: Store footprint in square meters.
- **Open Date**: Store open date.

### Exchange Rates
- **Date**: Date.
- **Currency**: Currency code.
- **Exchange**: Exchange rate compared to USD.


## Analysis Performed

1. **Top Product Analysis**: Identified the most popular products based on sales data. This can help in inventory management and marketing strategies.
2. **Average Order Value (AOV) Analysis**: Calculated the AOV for both online and retail stores to understand customer spending behavior. This can provide insights into pricing strategies.
3. **Revenue Analysis**: Tracked the revenue over the year to understand seasonal trends and overall growth.

## Tools Used

- **Excel**: Used for data management, analysis, and visualization. It helps in maintaining the dataset and generating insightful reports.

