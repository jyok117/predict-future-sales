# Predict Future Sales
**CS 636 Data Analytics with R Programming : Predict Future Sales**

[kaggle Link](https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales)

This project focuses on predicting future sales using a dataset from a Kaggle competition. The dataset includes historical sales data from a Russian software company, and the goal is to forecast total sales for every product and store in the next month.

## Objective
The primary objective is to use machine learning algorithms to predict sales based on historical data. This involves analyzing sales data on a yearly, monthly, and daily basis, identifying trends, and understanding the highest and lowest selling items and their market values.

## Data Processing
- **Cleaning**: Removing missing values to ensure data quality.
- **Merging**: Combining sales and item data using SQL-like joins to create a comprehensive dataset.

## Key Analysis Performed Include
- **Total Product Sold**: Evaluated on a yearly, monthly, and daily basis.
- **Sales Value**: Analyzed per year, month, and day to identify peak sales periods.
- **Item Popularity**: Identified items with the highest sales volume and price.

## Data Visualization
Data visualizations were created using libraries such as `ggplot`, `plotly`, and `dplyr` to represent sales trends and insights graphically.

## Machine Learning Model
A Linear Regression model was trained using features like shop ID, item ID, item price, and item category ID to predict sales. The model's performance was evaluated, with key metrics including p-value, R-squared, and adjusted R-squared.

## Conclusion
The analysis revealed that:
- The highest product sales occurred in 2013.
- Sales values peaked in 2014.
- Certain months consistently showed higher sales, suggesting seasonal trends.

The Linear Regression model provided significant predictions, though further improvement with other machine learning models is recommended. This project demonstrates the application of machine learning to predict sales, offering valuable insights into sales patterns and helping to inform future business strategies.
