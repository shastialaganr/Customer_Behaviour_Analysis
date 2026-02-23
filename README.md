# Customer_Behaviour_Analysis
End-to-end Customer Shopping Behavior Analysis using Python, PostgreSQL, and Power BI. Performed data cleaning, feature engineering, SQL-based business analysis, and built an interactive dashboard to uncover insights on revenue, customer segmentation, subscriptions, discounts, and product trends.

📌 Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories.
The objective is to uncover insights into:
Customer spending patterns
Product preferences
Subscription behavior
Discount impact
Revenue contribution by segment
The analysis was performed using Python, PostgreSQL (SQL), and Power BI.

📊 Dataset Summary
Total Records: 3,900
Total Columns: 18
Key Features:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Item, Category, Amount, Season, Size, Color)
Behavioral data (Discount, Frequency, Review Rating, Shipping Type)
Missing Data:
37 missing values in the Review Rating column (handled during data cleaning)

🐍 Data Analysis – Python (EDA & Cleaning)
Steps performed:
Data loading using pandas
Structure & summary analysis (df.info(), describe())
Missing value imputation (median rating by category)
Column renaming to snake_case
Feature engineering:
Created age_group
Created purchase_frequency_days
Removed redundant columns
Loaded cleaned data into PostgreSQL for SQL analysis

🗄️ Data Analysis – SQL (Business Insights)
Key business questions answered:
Revenue comparison by gender
High-spending customers using discounts
Top 5 highest-rated products
Shipping type purchase comparison
Subscriber vs Non-subscriber revenue analysis
Discount-dependent products
Customer segmentation (New, Returning, Loyal)
Top 3 products per category
Repeat buyers & subscription likelihood
Revenue contribution by age group

📈 Power BI Dashboard
An interactive dashboard was built to visualize:
Revenue trends
Customer segmentation
Product performance
Discount impact
Age-group contribution

💡 Business Recommendations
Promote subscription benefits
Introduce loyalty rewards for repeat customers
Optimize discount strategy
Highlight top-rated products in marketing
Target high-revenue age groups

🛠️ Tech Stack
Python (Pandas, Data Cleaning, Feature Engineering)
PostgreSQL (SQL Analysis)
Power BI (Dashboard & Visualization)
