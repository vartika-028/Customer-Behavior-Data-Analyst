# 🛍️ Customer Shopping Behavior Analysis

## 📌 Executive Summary
This project analyzes customer shopping behavior using transactional retail data to uncover actionable insights that can improve revenue, customer engagement, and retention. Using **Python for data preparation**, **SQL for business analysis**, and **Power BI for visualization**, the analysis identifies key purchase drivers such as discounts, subscriptions, shipping preferences, product ratings, and customer segments.

The insights help stakeholders make data-driven decisions related to marketing optimization, subscription growth, product positioning, and customer loyalty strategies.

---

## 🎯 Business Problem
A retail company aims to better understand customer purchasing patterns across demographics, product categories, and behavioral factors.

**Key Business Question:**
> How can customer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?

Challenges addressed:
- Identifying high-value customer segments  
- Understanding the impact of discounts and subscriptions  
- Recognizing top-performing and discount-dependent products  
- Improving customer retention and repeat purchases  

---

## 🧪 Methodology

### 1️⃣ Data Preparation & Feature Engineering (Python)
- Cleaned and standardized column names
- Handled missing values using **median imputation by product category**
- Created new features:
  - Age groups
  - Customer segments (New, Returning, Loyal)
  - Purchase frequency metrics
- Removed redundant columns
- Loaded cleaned data into **PostgreSQL** for SQL-based analysis

---

### 2️⃣ Data Analysis (SQL)
SQL queries were used to answer key business questions:
- Revenue by gender and age group
- Subscriber vs non-subscriber spending behavior
- High-spending discount users
- Top-rated and most purchased products
- Discount-dependent products
- Repeat purchase behavior and subscription likelihood
- Impact of shipping type on purchase value

---

### 3️⃣ Data Visualization (Power BI)
An interactive Power BI dashboard was built to visualize:
- Total customers, average purchase value, and average rating
- Revenue and sales by category and age group
- Subscription distribution
- Shipping preferences
- Customer segmentation



---

## 🛠️ Tools Used
- **Python:** pandas, NumPy (data cleaning, EDA, feature engineering)
- **SQL (PostgreSQL):** Joins, aggregations, CTEs, analytical queries
- **Power BI:** Dashboard design, DAX measures, data visualization


---

## 📈 Key Results & Insights
- Male customers generated higher total revenue compared to female customers
- Express shipping users showed slightly higher average purchase values
- Loyal customers formed the largest customer segment
- Discounts strongly influenced purchases for specific products
- Young adult and middle-aged customers contributed the highest revenue
- Top-rated products aligned closely with high sales volume

---

## 💡 Business Recommendations

### Core Recommendations
1. **Boost Subscriptions**
   - Promote exclusive benefits such as discounts, early access, or faster shipping

2. **Strengthen Loyalty Programs**
   - Reward repeat buyers to increase lifetime value

3. **Optimize Discount Strategy**
   - Avoid over-discounting high-performing products to protect profit margins

4. **Product Positioning**
   - Highlight top-rated and best-selling products in marketing campaigns

5. **Targeted Marketing**
   - Focus marketing efforts on high-revenue age groups and express-shipping users

---

## 📌 Conclusion
This project demonstrates how **Python, SQL, and Power BI** can be combined to convert raw transactional data into meaningful business insights. The analysis delivers actionable recommendations that can help retail businesses improve revenue, customer engagement, and long-term loyalty.
