Sales Data Analysis Report
1. Introduction
This report presents an in-depth analysis of sales data collected from a commercial store for the period of January to March 2024. The objective is to extract meaningful insights using data analysis techniques and visualization tools like Power BI.
________________________________________
2. Data Collection
•	The dataset was created manually to simulate real-world sales transactions.
•	Key attributes included: 
o	Date: Sales transactions from January to March 2024.
o	Location: Different store branches.
o	Product Name & Category: Various product categories.
o	Quantity Sold & Unit Price: Details on product sales.
o	Total Sales: Computed as Quantity Sold × Unit Price.
o	Way of Payment: Modes like Cash, Credit Card, and Online Transactions.
________________________________________
3. Data Cleaning & Preprocessing
The following steps were taken to clean the dataset using Jupyter Notebook (Python - Pandas & Matplotlib):
1.	Loaded the dataset using Pandas.
2.	Checked for missing values and used forward-fill method (ffill()) to handle them.
3.	Converted Date column to datetime format (pd.to_datetime()).
4.	Standardized column names for consistency.
5.	Saved the cleaned dataset as sales_data_cleaned.csv.
________________________________________
4. Exploratory Data Analysis (EDA)
Key Insights from Data Analysis
•	Total Sales by Location: Identified which store branch performed the best.
•	Best-Selling Products: Found the most in-demand products.
•	Sales Trend Over Time: Analyzed the sales growth pattern.
•	Payment Method Preference: Determined the most preferred payment mode.
________________________________________
5. Dashboard & Visualizations in Power BI
To visualize the findings, the following charts were created in Power BI:
1.	Total Sales by Location → Bar Chart
2.	Best-Selling Products → Column Chart
3.	Sales Trend Over Time → Line Chart
4.	Sales by Payment Method → Pie Chart
5.	Sales by Product Category → Ribbon Chart (Alternative to Treemap)
________________________________________
6. Business Recommendations
Based on the insights obtained:
•	Optimize inventory management by stocking more of the best-selling products.
•	Focus marketing efforts on locations with lower sales performance.
•	Enhance digital payment options due to rising online transactions.
•	Plan promotions around the peak sales trends identified in the dataset.
________________________________________
7. Conclusion
This analysis provided valuable insights into sales performance trends, customer preferences, and store efficiency. The visualizations and recommendations will help the business make data-driven decisions to maximize revenue and enhance customer experience.
________________________________________
Prepared By: Durga Sanjay
Date: February 2025

