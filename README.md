# Sales Data Analysis using Python

This project demonstrates a basic data analysis workflow using Python.  
The analysis was performed using Pandas for data manipulation and Matplotlib for visualization.

## Project Objectives

The main objectives of this project are:

- Perform data cleaning by handling missing values
- Identify and remove duplicate records
- Analyze sales data based on product categories
- Examine payment method usage
- Understand customer distribution by city and age
- Visualize the data using charts

## Dataset Information

The dataset contains sales-related information including:

- Customer Age
- Gender
- City
- Product Category
- Price
- Quantity
- Payment Method

The dataset was cleaned and processed before performing analysis.

## Tools and Libraries Used

- Python
- Pandas
- Matplotlib
- Google Colab

## Data Cleaning Steps

The following preprocessing steps were performed:

- Missing values in **Age** were replaced using the mean value.
- Missing values in **City** were replaced using the most frequent value.
- Remaining missing values were filled with zero.
- Duplicate rows were identified and removed.
- Numeric columns were converted to integer data type.

## Data Analysis

Several analyses were performed on the dataset:

- Total sales calculation
- Sales by product category
- Payment method frequency
- City-wise order distribution
- Average age of customers

## Data Visualization

The following charts were created to better understand the data:

- Bar chart showing **Total Sales by Product Category**
- Pie chart showing **Payment Method Distribution**
- Histogram showing **Age Distribution**

## Insights

- Electronics category generated the highest total sales.
- UPI was the most commonly used payment method.
- Most customers fall in the age group of approximately 22–26.
- Visakhapatnam had the highest number of orders among the cities.

## Conclusion

This project demonstrates how basic data cleaning, analysis, and visualization techniques can be applied to understand patterns in sales data. Using Python libraries such as Pandas and Matplotlib makes it easier to process and interpret data efficiently.

## Future Improvements

- Use Seaborn or Plotly for more advanced visualizations
- Perform deeper analysis on customer behavior
- Build predictive models using machine learning
