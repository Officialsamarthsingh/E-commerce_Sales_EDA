# E-Commerce Sales Exploratory Data Analysis (EDA)

## Project Overview
  This project focuses on Exploratory Data Analysis (EDA) of an E-Commerce Sales dataset to identify sales trends,customer purchasing behavior, category performance,
and revenue-driving factors.

The analysis helps businesses understand:
- Which products perform best
- Which cities generate highest revenue
- Customer purchasing patterns
- Monthly and yearly sales trends
- Key business KPIs

 ## Business Problem Statement
   E-commerce businesses generate large amounts of transactional data. Without proper analysis, it becomes difficult to identify:

- High-performing categories
- Revenue trends
- Customer behavior
- Peak sales periods
- High-value customers

The goal of this project is to perform data analysis and generate actionable business insights to support better decision-making.

## Objectives
- Perform data cleaning and preprocessing
- Analyze sales trends over time
- Identify top-performing categories
- Discover high-revenue cities
- Calculate business KPIs
- Understand customer purchasing behavior
- Generate business recommendations

## Dataset Information
  The dataset contains e-commerce transaction records including:

- Order Date
- Product Category
- Product Price
- Quantity
- Customer Information
- City
- Sales Data

Dataset Size:
- Rows: 5000
- Columns: 10

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow
1. Data Collection
2. Data Understanding
3. Data Cleaning
4. Feature Engineering
5. Exploratory Data Analysis
6. Visualization
7. KPI Analysis
8. Business Insights
9. Recommendations

## Data Cleaning
   The following preprocessing steps were performed:
- Checked missing values
- Checked duplicate records
- Standardized column names
- Converted date columns into datetime format
- Created new features such as:
  - Order Month
  - Order Year
  - Total Sales Amount

## Feature Engineering
   New columns were created to improve analysis:
- order_month
- order_year
- total_price
  
These features helped in:
- Monthly trend analysis
- Yearly comparison
- Revenue calculations

## Exploratory Data Analysis
   The following analyses were performed:

### Univariate Analysis
- Sales distribution
- Product category frequency
- Quantity distribution

### Multivariate Analysis
- Category vs Revenue
- Monthly sales trends
- City-wise sales analysis
- Yearly sales comparison

### Key KPIs

| KPI               |  Value          |
|-------------------|-----------------|
| Total Revenue     | ₹593.17 Million |
| Total Orders      | 5,000           |
| AverageOrderValue | ₹118,634        |
| Top City          | Bangalore       |
| HighestSalesMonth | May             |


## Key Insights
   - Bangalore generated the highest overall revenue.
- May was the highest-performing sales month.
- Books and Kitchen categories had the highest order volumes.
- A small percentage of customers contributed a large share of revenue.
- Sales showed seasonal fluctuations across the year.

## Visualizations
  The project includes:
- Sales Trend Analysis
- Revenue Distribution Histogram
- Category-wise Sales Charts
- City-wise Revenue Analysis
- Customer Spending Analysis
- Quantity Distribution Boxplots
- Analysing correlation using Heat map
  
## Business Recommendations
   - Increase marketing during peak sales months
- Expand operations in high-performing cities
- Improve inventory planning for top categories
- Introduce loyalty programs for premium customers.
- Use customer segmentation for targeted promotions.

## Conclusion
   This project demonstrates how Exploratory Data Analysis can help businesses identify revenue opportunities, understand customer behavior, and improve operational decision-making using data-driven insights.
