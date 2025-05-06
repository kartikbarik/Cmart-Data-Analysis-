
# CMART DATASET ANALYSIS USING POWER BI
This project leverages Power BI to perform in-depth analysis of the CMart dataset, uncovering trends, customer behavior, and sales insights through interactive dashboards and visualizations.

## Overview
- **Data Cleaning & Preparation**: Handling missing values and formatting data for Power BI
- **Interactive Dashboard**: Visualization of sales performance and customer trends
- **DAX Measures**: Custom calculations for deeper insights
- **Filters & Slicers**: Dynamic exploration of key metrics

## Dataset Describtion
The CMart dataset consists of:
- `Product_Name` - Unique identifier for each product
- `Category` - Product category
- `Sub_Category` - Product Sub_category
- `Profit` - Product profit
- `Sale` - Product sale
- `Customer_Name` - Unique identifier for each customer
- `Customer_Type` - Customer Type
- `Country & State` - country and State



## Power BI Analysis Workflow
1. **Data Import**: Load dataset into Power BI
2. **Data Cleaning**: Handle missing values, create calculated columns
3. **Dashboard Design**:
   - **Sales Performance**: Monthly revenue trends
   - **Customer Insights**: Segmentation based on purchase patterns
   - **Product Analysis**: Top-performing products and categories
4. **DAX Formulas**:
   - `Total_Order = COUNTROWS('Order Data CMart')`
   - `Total_Sales = SUMX('Order Data CMart','Order Data CMart'[Sales]*'Order Data CMart'[Quantity])`
 

## Results & Insight 
- Sales Growth Trends: Identified peak sales periods
- Customer Behavior: Recognized top spending groups
- Product Performance: Highlighted best-selling products

## Contact Details 
For inquiries, reach out via [kartikbarik603@gmail.com].

Does this align with your expectations? Let me know if you'd like to refine any section!
