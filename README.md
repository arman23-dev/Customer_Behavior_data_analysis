# Customer_Behavior_data_analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional data from ~3,900 purchases. The objective is to uncover patterns in customer spending, product preferences, and subscription behavior to support data-driven business decisions.

🎯 Business Problem

A retail company wants to understand customer purchasing behavior to:

Improve sales performance
Increase customer satisfaction
Build long-term customer loyalty

❓ Key Question:
How can consumer shopping data be used to identify trends, improve engagement, and optimize marketing strategies?

📊 Dataset Summary
📁 Total Records: 3,900
📊 Total Columns: 18

🔑 Key Features:
Customer Demographics (Age, Gender, Location)
Purchase Details (Item, Category, Amount, Season)
Behavior Data (Discounts, Frequency, Reviews, Shipping Type)

⚠️ Missing Values:
37 missing values in review_rating column (handled during preprocessing)

⚙️ Tech Stack
Python (Pandas, NumPy)
PostgreSQL
Power BI
Excel
Jupyter Notebook

🧹 Data Preparation (Python)
Loaded dataset using Pandas
Performed data cleaning and preprocessing
Handled missing values using median imputation
Standardized column names (snake_case)
Feature Engineering:
Created age_group
Created purchase_frequency_days
Removed redundant columns
Exported cleaned data to PostgreSQL

🗄️ Data Analysis (SQL)

Performed business-driven analysis using SQL:

📈 Revenue analysis by gender
💰 Identified high-spending discount users
⭐ Top-rated products
🚚 Shipping type comparison (Standard vs Express)
🔁 Subscriber vs non-subscriber analysis
🏷️ Discount-dependent products
👥 Customer segmentation (New, Returning, Loyal)
🛍️ Top products per category
🔄 Repeat purchase behavior & subscriptions
📊 Revenue by age group
📊 Dashboard (Power BI)

Built an interactive dashboard to visualize:
Sales trends
Customer segments
Product performance
Subscription insights

💡 Key Insights
Subscribers tend to generate higher revenue
Discount strategies influence purchasing behavior
Certain age groups contribute significantly to revenue
Loyal customers show higher repeat purchase rates

📌 Business Recommendations
🎯 Promote subscription benefits to increase retention
🎁 Implement loyalty programs for repeat customers
💸 Optimize discount strategies to balance profit and sales
🛍️ Highlight top-rated and best-selling products
📍 Focus marketing on high-value customer segments
