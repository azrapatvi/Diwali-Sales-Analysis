# 🪔 Diwali Sales Data Analysis

## 📌 Project Overview
This project analyzes **Diwali sales data** using Python to uncover customer purchasing behavior and sales trends.  
The analysis includes **data cleaning, exploratory data analysis (EDA), and visualizations** to highlight spending patterns, customer demographics, and seasonal trends.

## 📂 Dataset
The dataset contains transaction details such as:
- Customer information (ID, Name, Gender, Age Group, etc.)
- Product details
- Order amount
- Transaction date  

Unnecessary or sensitive columns (like `User_ID`, `Cust_name`) were removed during cleaning.

## 🛠 Workflow

### 1. Data Cleaning
- Removed irrelevant columns (`Status`, `unnamed1`, etc.)
- Handled missing values (`Amount` column filled with mean values)
- Converted date column into datetime format
- Dropped duplicates  

### 2. Exploratory Data Analysis (EDA)
- **Sales Over Time** → Line chart showing revenue trends across the year  
- **Monthly Spending Trend** → Aggregated monthly revenue with clear seasonal spikes  
- **Customer Demographics** → Gender, age group, and state-wise analysis  
- **Top Performing States & Occupations** → Insights into customer base  
- **Product Categories** → Most purchased and high-revenue categories  

### 3. Visualizations
- Line charts for time-series sales trends  
- Bar plots for customer demographics  
- Pie charts for category-level contribution  

## 📊 Key Insights
- Peak sales occur during the **Diwali season** (Oct–Nov).  
- Female customers contribute higher average spending compared to males.  
- Customers in the **age group 26–35** are the most active buyers.  
- **Maharashtra, Uttar Pradesh, and Karnataka** are top-performing states.  
- **Food, Clothing, and Electronics** dominate product sales.  

## 🚀 Conclusion
The analysis highlights **who the primary customers are and when sales peak**, which helps in targeting **marketing campaigns and stock management during festive seasons.**
