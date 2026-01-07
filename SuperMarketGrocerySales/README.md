#  Supermart Grocery Sales Analysis using Python

##  Project Overview
This project performs an exploratory data analysis (EDA) on supermarket grocery sales data to understand sales performance, seasonal trends, city-wise contribution, and the impact of discounts on profitability.  
The analysis is implemented using Python in Jupyter Notebook with Pandas and Matplotlib.



##  Objectives
- Analyze total sales across different product categories  
- Identify monthly and yearly sales trends  
- Find top-performing cities based on sales  
- Understand the relationship between discount and profit  



##  Dataset Description
The dataset contains order-level grocery sales data with the following key columns:
- Order ID  
- Order Date  
- Category & Sub-Category  
- City & Region  
- Sales  
- Discount  
- Profit  



## Data Cleaning & Preprocessing
- The **Order Date** column was initially stored as text.
- It was converted into a proper datetime format using Pandas.
- **Month** and **Year** were extracted from Order Date to enable time-based analysis.
- The dataset was checked for missing values and duplicates.



##  Exploratory Data Analysis

## 1.Total Sales by Category
- Eggs, Meat & Fish emerged as the highest revenue-generating category.
- Snacks also showed strong sales performance.
- Oil & Masala recorded comparatively lower sales.

##2. Monthly Sales Trend
- Sales are lowest during January and February.
- A significant increase is observed from September onwards.
- Peak sales occur in November, indicating festive season demand.

### 3.Sales Distribution by Year
- Sales show consistent growth from 2015 to 2018.
- The year 2018 contributes the highest share of total sales.

## 4. Top 5 Cities by Sales
- A small number of cities contribute a large portion of total revenue.
- These cities represent high-potential markets for targeted business strategies.

##5.Profit vs Discount Analysis
- A negative relationship is observed between discount and profit.
- Higher discounts generally reduce profit margins.
- Discounts should be optimized carefully to balance sales growth and profitability.



##  Key Insights
- Sales exhibit strong seasonality.
- Certain product categories and cities dominate revenue.
- Excessive discounting negatively impacts profit.
- Correcting date formats is crucial for accurate time-based analysis.



## Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook  

---

##  Project Structure
Supermart-Grocery-Sales-Analysis/
│
├── Supermart_Grocery_Sales_Analysis.ipynb
├── dataset.csv
├── graphs/
│ ├── category_sales.png
│ ├── monthly_sales_trend.png
│ ├── sales_by_year.png
│ ├── top_5_cities.png
│ └── profit_vs_discount.png
└── README.md



##  Conclusion
This project demonstrates a complete data analysis workflow, including data cleaning, exploratory analysis, visualization, and business insight generation.  
It showcases essential skills required for an entry-level Data Analyst role.



# Author
Sneha PB 
snehapb25@gmail.com 
  

