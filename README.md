# Swiggy Sales Analysis Dashboard

An interactive Excel dashboard analyzing Swiggy food delivery sales data, built to identify sales trends, city-wise performance, and restaurant-level insights using pivot tables, charts, and slicers.

## Project Overview

This project analyzes Swiggy food delivery sales data using Microsoft Excel to identify sales trends, category performance, and regional insights. The goal is to transform a large raw dataset into meaningful business insights through data preparation, analysis, and an interactive dashboard.

## Dataset

The dashboard is built on `Swiggy_Raw_Data_Excel.xlsx`, a food delivery sales dataset with approximately 197,000 records and the following fields:

| Column | Description |
|---|---|
| State | State where the order was placed |
| City | City where the order was placed |
| Order Date | Date the order was placed |
| Restaurant Name | Name of the restaurant |
| Location | Area or locality within the city |
| Category | Food category of the dish |
| Dish Name | Name of the dish ordered |
| Price (INR) | Price of the dish |
| Rating | Customer rating for the restaurant |
| Rating Count | Number of ratings received |

This is a practice dataset used for analytical and portfolio purposes.

## Data Preparation

- Converted date fields into month, week, and quarter formats
- Created calculated fields such as Total Sales, Average Price per Order, and Quarter
- Ensured correct data types for numerical and date columns
- Derived Veg / Non-Veg classification using keyword-based logic on dish names (for example, chicken, murgh, gosht, egg handling); this classification may differ from predefined categorizations used elsewhere

## Key Performance Indicators

The dashboard tracks the following primary KPIs:

- **Sales (Rs.)**: Total revenue generated across all orders (Rs. 53,012,505)
- **Number of Orders**: Total count of orders placed (197,430)
- **Average Price per Order**: Average revenue per order (Rs. 268.51)

## Features

- **Filter Panel**: Filter data by month, city, location, and restaurant name, with a one-click reset filter option
- **Top 5 Cities**: Highlights the highest revenue-generating cities, led by Bengaluru, Lucknow, Hyderabad, Mumbai, and New Delhi
- **Monthly Trend**: Line chart tracking total sales across months
- **Weekly Trend**: Bar chart tracking total sales across 36 weeks
- **Daily Trend**: Bar chart comparing total sales by day of the week
- **Top 5 Items Revenue**: Table showing the highest revenue items along with total sum, average price, and number of orders
- **Total Sales and Rating Summary**: Quarter-wise breakdown (Q1, Q2, Q3) of total sales and average rating, with a grand total

## Analysis Performed

- Monthly, weekly, and daily sales trend analysis
- Sales comparison by Veg vs Non-Veg
- State-wise and city-wise sales performance
- Identification of top-performing cities by total sales
- Quarterly comparison of sales, orders, and ratings
- Restaurant-level and item-level sales analysis

## Key Insights

- Sales show clear monthly and weekly trends, with most weeks tracking closely around the Rs. 1.5M mark
- A small number of cities, led by Bengaluru, contribute a significant portion of total revenue
- Veg and Non-Veg categories show different revenue distributions
- Certain restaurants and combo items, such as Choley Bhature and Thali Feast combos, consistently outperform others in sales
- Quarterly performance remained consistent, with an average rating of 4.34 across all three quarters

## Tools Used

- **Microsoft Excel**: Dashboard design and data visualization
- **Pivot Tables and Pivot Charts**: Data summarization and trend analysis
- **Excel Formulas**: Data transformation and calculated fields

## Repository Contents

| File | Description |
|---|---|
| `Swiggy_Raw_Data_Excel.xlsx` | Raw source dataset |
| `Swiggy.xlsx` | Cleaned and prepared dataset used for analysis |
| `Dashboard.xlsm` | Interactive Excel dashboard (macro-enabled) |
| `Dashboard_Excel.png` | Screenshot of the Excel dashboard |
| `Swiggy_Sales_Analysis.docx` | Project documentation and dashboard summary |
| `README.md` | Project overview and documentation |

## How to Use

1. Clone this repository
2. Open `Dashboard.xlsm` in Microsoft Excel (enable macros if prompted) to explore the interactive dashboard
3. Use the filter panel to explore sales performance by month, city, location, and restaurant name

## Note

This analysis was conducted as part of a project and is for educational purposes only.
