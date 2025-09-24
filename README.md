# Telecom Churn Analysis (Excel Project)

## 📌 Project Overview
This project analyzes customer churn using Excel.  
The aim is to understand which factors influence churn and to visualize patterns that can guide retention strategies.

## 📂 Dataset
The dataset contains customer details such as:
- Account length  
- Customer service calls  
- Total day/evening/night/international calls, minutes, and charges  
- Churn status (Yes/No)

## 🔧 Tools Used
- Microsoft Excel 2013  
  - Data cleaning  
  - PivotTables  
  - Calculated fields (e.g., Total Usage, Usage Groups)  
  - Charts (Column, Bar, Scatter Plot)  
  - Dashboard design  

## 📊 Analysis Performed
1. **Data Cleaning**  
   - Removed duplicates and checked for missing values  
   - Created a new column for **Total Usage** (sum of day, evening, night, and international minutes)  
   - Grouped customers into usage categories (Low, Medium, High)  

2. **Churn Rate**  
   - Calculated churn rate = number of churned customers ÷ total customers  

3. **Churn vs Customer Service Calls**  
   - Created a column chart to show how churn increases with the number of service calls  

4. **Churn vs Account Length**  
   - Analyzed whether newer or older customers are more likely to churn  

5. **Churn vs Total Usage Groups**  
   - Compared churn across low, medium, and high usage customers  

6. **Scatter Plot (Usage vs Charges)**  
   - Built a scatter plot separating churned vs non-churned customers  
   - Observed where churned customers cluster  

## 🔎 Key Insights
- Customers with **more customer service calls** are more likely to churn.  
- **Shorter account length** customers churn more often.  
- Churn is slightly higher in certain **usage groups**, though customer service calls remain the strongest factor.  
- Scatter plot shows churned customers often cluster in specific usage/charge ranges.  

## ✅ Conclusion
Customer service quality and account length are strong drivers of churn.  
Improving support and focusing on newer customers could reduce churn significantly.
