☕ Café Sales Analytics Dashboard

📌 Project Overview
This project focuses on transforming a dirty, real-world café sales dataset into a business-ready analytical dashboard.
The goal was to demonstrate end-to-end data analytics skills — from data cleaning and auditing to visualization and business insights.

📂 Dataset
Source: Café Sales – Dirty Data for Cleaning Training (Kaggle) 
Description: Daily transactional sales data from a café chain
Initial Rows: 10,000
Final Clean Rows: 7,774

🧪 Data Audit & Cleaning Summary
🔴 Issues Identified
Inconsistent casing (e.g., coffee / Coffee / COFFEE)
Wrong data types (numeric values stored as strings)
Missing values in business-critical columns
Invalid placeholders (ERROR, UNKNOWN)
Logical inconsistencies (Total Spent ≠ Quantity × Price)
Missing or invalid transaction dates

🟢 Cleaning Actions
Replaced invalid placeholders with null values
Converted columns to appropriate numeric and datetime types
Removed invalid transactions (missing item, price, quantity, or date)
Recalculated Total Spent using business logic
Standardized categorical fields (Item, Location, Payment Method)
Performed post-cleaning validation checks
Data Retention: ~78% (7,774 valid records)

🛠️ Tools & Technologies
Python: Pandas, NumPy (data cleaning & audit)
Power BI: Data modeling, DAX, dashboard design
DAX Measures:
Total Revenue
Total Transactions
Units Sold
Average Order Value (AOV)
Image URL columns for enhanced visuals

📊 Dashboard Features
Single-page executive dashboard
KPI cards for revenue, transactions, units sold, and AOV
Quarterly & monthly revenue trends
Revenue contribution by product
Location-wise and payment-method analysis
Scatter plot for pricing vs quantity by location
Image-based slicers for intuitive filtering
Coffee-themed UI aligned with business domain

📈 Key Business Insights & Recommendations
1. Quarter 4 Generates the Highest Revenue
Data: Q4 revenue (~17.7K) > Q3 (~17.1K)
Recommendation: Increase staffing, inventory, and promotions during Q4.

2. Food Items Outperform Beverages
Data: Salad (15K), Sandwich (12K), Smoothie (12K) vs Coffee (6K)
Recommendation: Promote meal combos and prioritize food items during peak hours.

3. High Revenue from “Unknown” Location
Data: Unknown (27.63K) > In-Store (21.32K)
Recommendation: Improve POS location data capture for operational clarity.

4. Payment Method Data Gaps
Data: Unknown payment method contributes 22K revenue
Recommendation: Enforce mandatory payment selection and promote digital payments.

5. Takeaway Orders Show Higher Pricing Efficiency
Insight: Higher unit price despite lower quantity
Recommendation: Introduce premium packaging or add-ons for takeaway orders.

🎯 Key Learnings
Data quality directly impacts business decisions
Cleaning logic must be business-driven, not just technical
A well-designed single-page dashboard can deliver powerful insights
Analytics is as much about storytelling as it is about numbers

📎 Files in This Repository
code.ipynb → Python data cleaning & audit
Cafe Dashboard Image
Documentation

Author: Jyoti Gupta
Linked-In: https://www.linkedin.com/in/jyotigupta-da/

documentation.txt → Project notes & insights
