# Task 2: E-commerce Sales Data Analysis using the Online Retail Dataset

## Objective

You've been given a dataset that contains sales transactions from an online retail store. Your goal is to analyze this data, extract meaningful insights, and present your findings using Python and relevant data visualization tools.

## Dataset

You will be working with the `Online Retail.xlsx` dataset. The dataset contains the following columns:

- **InvoiceNo**: Invoice number. A unique identifier for each transaction.
- **StockCode**: Product (item) code.
- **Description**: Product (item) name.
- **Quantity**: Number of products purchased in the transaction.
- **InvoiceDate**: Timestamp for when the transaction was generated.
- **UnitPrice**: Price per product unit.
- **CustomerID**: Unique identifier for each customer.
- **Country**: Country from which the order was placed.

## Tasks

### 1. Data Loading & Cleaning

- Load the dataset from the Excel file.
- Handle any missing values and perform necessary data cleaning steps.

### 2. Data Analysis

- Compute the total sales for each product and rank them in descending order.
- Identify the top 5 customers based on total purchase value.
- Determine which month saw the highest sales.
- Identify the most frequently purchased product (in terms of quantity).
- Find out the day of the week with the highest average sales.

### 3. Data Visualization

- Plot a bar graph to showcase the sales figures of the top 10 products.
- Create a line graph that illustrates the monthly sales trends.
- Present a bar graph to visualize the average sales figures based on days of the week.

## Tips

- Use the `pandas` library for data manipulation and analysis.
- Leverage `matplotlib` or `seaborn` for data visualization.


**Note**: While working through the tasks, consider potential exceptions and edge cases to ensure your analysis is robust and can handle unexpected challenges.
