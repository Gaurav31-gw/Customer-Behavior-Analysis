🛍️ Customer Shopping Behavior Analysis
📌 Project Overview

This project focuses on analyzing customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover meaningful insights into:

💸 Spending patterns
👥 Customer segments
🛒 Product preferences
🔁 Subscription behavior

These insights help in making data-driven business decisions.

📊 Dataset Summary
Feature	Details
📄 Rows	3,900
📊 Columns	18
⚠️ Missing Values	37 (Review Rating column)
🔑 Key Attributes:
👤 Customer Demographics: Age, Gender, Location, Subscription Status
🛍️ Purchase Details: Item, Category, Amount, Season, Size, Color
📈 Behavior Metrics: Discount, Promo Code, Purchase Frequency, Rating, Shipping Type
🧹 Data Preprocessing (Python)

Performed using Pandas & NumPy:

📥 Data Loading using pandas
🔍 Initial Exploration using .info() and .describe()
❌ Missing Value Handling (median imputation for ratings)
🏷️ Column Standardization (snake_case format)
⚙️ Feature Engineering:
Age groups classification
Purchase frequency conversion
🔄 Data Cleaning:
Removed redundant columns (promo_code_used)
🗄️ Database Integration:
Loaded cleaned data into PostgreSQL
🧠 SQL Analysis (Business Insights)

Key business questions answered using SQL:

📊 Insights Extracted:
👨‍🦱👩 Revenue by Gender
💰 High-Spending Discount Users
⭐ Top 5 Products by Rating
🚚 Shipping Type Comparison (Standard vs Express)
🔔 Subscribers vs Non-Subscribers Analysis
🏷️ Discount-Dependent Products
👥 Customer Segmentation (New, Returning, Loyal)
🛒 Top Products per Category
🔁 Repeat Buyers vs Subscription Behavior
🎯 Revenue by Age Group

👉 Example (from analysis):

Male customers generated higher revenue than female customers (page 3)
Express shipping users tend to spend slightly more (page 4)
Loyal customers dominate the dataset (page 5)
📈 Power BI Dashboard

An interactive dashboard was created to visualize insights effectively.

🔍 Key Dashboard Metrics:
👥 Total Customers: 3.9K
💵 Average Purchase: $59.76
⭐ Average Rating: 3.75
📊 Visuals Included:
Revenue by Category 📊
Sales by Category 📉
Revenue by Age Group 👥
Subscription Distribution 🔔
Filters for dynamic analysis 🎛️

Based on analysis:

🔔 Boost Subscriptions
→ Offer exclusive benefits & discounts
🎁 Customer Loyalty Programs
→ Reward repeat buyers
⚖️ Optimize Discount Strategy
→ Balance revenue vs profit
🛍️ Product Positioning
→ Promote top-rated & best-selling items
🎯 Targeted Marketing
→ Focus on high-value age groups & users
🛠️ Tech Stack
🐍 Python (Pandas, NumPy)
🗄️ PostgreSQL
📊 Power BI
💻 SQL
