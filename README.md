# Superstore-Sales-Analysis-R-Programing
## 🔍 1. Project Objective

The study explores hidden patterns in sales, returns, and customer sentiment using a dataset of 1,000 observations. It introduces novel metrics like:

#### Performance Index

#### Inventory Stress

#### Satisfaction-Return Ratio

These metrics aim to go beyond simple KPIs to support strategic, data-driven business decisions.


## 🛠 2. Methodology

#### A. Data Cleaning

Removed extra spaces and special characters in text fields (e.g., Product_Category, Brand_Special)

Converted values to appropriate types (e.g., numeric for Sales_Amount)

Used median imputation for missing values in Customer_Satisfaction and Return_Rate, grouped by product and brand (more robust to outliers)

Rounded numerical fields to enhance clarity

#### B. Feature Engineering

Three new metrics were introduced:

Satisfaction_Return_Ratio = Satisfaction ÷ Return Rate → balances user happiness against return behavior

Performance_Index = Combines sales, satisfaction, and returns into a composite score

Inventory_Stress = Stock Level ÷ Sales → assesses how well inventory is moving


## 📊 3. Exploratory Data Analysis (EDA)

A variety of ggplot2 visualizations were created to derive insights:

##### A. Customer Satisfaction

Most customers are satisfied or very satisfied

##### B. Return Rate Patterns

Majority of products fall in moderate (9–11.5%) or high (11.5–14%) return groups

Very few items have low return rates → indicating possible quality or expectation mismatch

##### C. Sales Insights

Clothing generates the highest average sales, followed by Furniture

##### D. Performance Index Trends

Products with lower return rates generally score higher on Performance Index

Clothing shows high variability in performance, indicating potential inconsistency

##### E. Inventory Efficiency

High Inventory Stress is negatively correlated with Sales → suggests overstocked items are not performing well

##### F. Brand Analysis

“Retail X” generally performs well across multiple metrics

“Outlet Y” shows lower satisfaction and performance → might require review or support


## 🧠 4. Strategic Business Recommendations

Reduce stock for low-performing, high-stress items

Improve product info, especially for categories with high returns like Clothing

Promote strong brands (e.g., Retail X), reevaluate weaker ones

Engage with “neutral” customers to convert them to loyal ones

Use interactive dashboards to monitor these metrics for better decision-making
