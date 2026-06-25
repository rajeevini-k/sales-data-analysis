End-to-end Sales Data Analysis using Python. Includes data preprocessing, exploratory data analysis (EDA), revenue analysis, visualization using Matplotlib, and automated business insights generation.
Sales Data Analysis Project
Author
Rajeevini K

Project Overview

This project performs "Sales Data Analysis" using Python.  
It demonstrates how raw sales data can be transformed into meaningful business insights using data analysis techniques.

The project includes:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Revenue analysis by product, city, and category
- Data visualization using charts
- Automated business insights generation
- Exporting analytical reports

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
Dataset Description

The dataset contains sales transaction details:

- Order ID
- Date
- Product
- Category
- City
- Quantity
- Price

A sample dataset is generated within the notebook for demonstration purposes.
Key Analysis Performed

1. Data Processing
- Converted date fields to datetime format
- Created revenue column (Quantity × Price)
- Extracted month from date

2. Exploratory Data Analysis (EDA)
- Total revenue calculation
- Product-wise revenue analysis
- City-wise revenue analysis
- Category-wise revenue analysis
- Monthly sales trends

3. Visualization
- Monthly revenue trends
- Top performing products
- City-wise revenue comparison
- Category distribution (Pie chart)

Business Insights (Dynamic Output)

The project automatically generates insights such as:
- Top performing product based on revenue
- Top performing city
- Highest revenue-generating category
- Lowest performing product and city
- Revenue contribution percentages
- Monthly growth trend (increase/decrease)

Sample Visualizations

After running the notebook, the following charts are generated:

- Monthly Revenue Bar Chart
- Product Revenue Bar Chart
- City Revenue Bar Chart
- Category Revenue Pie Chart

Output Files Generated

- sales_data.csv
- product_sales_report.csv
- city_sales_report.csv
- category_sales_report.csv
- monthly_sales_report.csv
- monthly_sales.png
- top_products.png
- sales_by_city.png
- category_share.png

How to Run This Project

Option 1: Google Colab (Recommended)
1. Open Google Colab
2. Upload the notebook file
3. Run all cells
4. Download outputs and visualizations

Option 2: Local System
- pip install pandas numpy matplotlib
- python sales_analysis.py
