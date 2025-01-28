# E-Commerce Sales Performance Dashboard

## Project Overview
This project involves creating a professional Power BI dashboard to analyze and visualize sales data for an e-commerce platform. The goal is to provide actionable insights into sales performance, customer behavior, and revenue trends to help stakeholders make informed business decisions.

## Objectives
- To analyze key sales metrics, including revenue, product performance, and customer trends.
- To identify high-performing regions, products, and customer segments.
- To provide interactive filters for better data exploration.

## Tools Used
- **Microsoft Power BI**: For creating the interactive dashboard.
- **Microsoft Excel**: For initial data cleaning and preparation.

## Data Sources
The dataset used for this project is based on an e-commerce sales dataset from UCI Machine Learning Repository (Online Retail) that includes the following fields:
- **InvoiceNo**: Unique identifier for each transaction.
- **StockCode**: Product code.
- **Description**: Product name.
- **Quantity**: Number of items sold.
- **InvoiceDate**: Date of transaction.
- **UnitPrice**: Price per item.
- **CustomerID**: Unique identifier for each customer.
- **Country**: Customer's location.

## Data Cleaning
The dataset underwent the following cleaning steps:
1. Removed negative or zero values in the "Quantity" and "UnitPrice" columns.
2. Removed rows with missing values in critical columns such as "CustomerID and "Description".
3. Extracted additional fields from "InvoiceDate":
   - **Year**
   - **Month**
   - **Day of Week**
4. Created a new column named "Revenue".

## Key Features of the Dashboard
- **Sales Overview**: Displays total revenue, total units sold, and no. of unique customers.
- **Top Products**: Highlights the top 5 best-selling products.
- **Top Customers**: Highlights the top 5 contributing to total revenue.
- **Geographic Insights**: Interactive map showing revenue distribution by country.
- **Time-Based Trends**: Sales trends over months and years.
- **Filters**:
  - Region (country) slicer.

## How to View the Dashboard
1. Download the `.pbix` file from the provided link.
2. Open the file in Microsoft Power BI Desktop.

Here is the dashboard: 
![SS1](https://github.com/user-attachments/assets/5667deae-9d9a-431c-986c-854e20eb8d0c)
![SS2](https://github.com/user-attachments/assets/b951f7c6-619b-4084-9426-8ee9e5beb933)
![SS3](https://github.com/user-attachments/assets/5fffd460-ca3c-42f2-8153-5648e6c3f87d)
![SS4](https://github.com/user-attachments/assets/03b18bbe-583e-4eff-b50f-e9fcd85e9bab)
![SS5](https://github.com/user-attachments/assets/e39be7aa-8947-4d54-a6aa-4750761e7fd2)


