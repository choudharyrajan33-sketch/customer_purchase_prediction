# 🛍️ Customer Purchase Prediction & Behaviour Analysis

## 📌 Project Overview

An end-to-end Machine Learning project that analyzes customer behavior patterns and predicts whether a customer will make a purchase based on demographic, behavioral, and contextual features. This project demonstrates a complete real-world ML workflow from data exploration to business recommendations.

**Domain:** Retail / E-Commerce  
**Problem Type:** Binary Classification  
**Target Variable:** Purchase (0 = No Purchase, 1 = Purchase)

## 🎯 Problem Statement

A retail company wants to:
1] **Understand customer behavior** patterns from their website interactions
2] **Predict purchase decisions** to optimize marketing strategies
3] **Increase conversion rates** through data-driven insights

**Business Challenge:**  
The company has thousands of visitors daily but only a fraction make purchases. By predicting which customers are likely to purchase, the company can:
1] Target high-probability customers with personalized offers
2] Reduce cart abandonment
3] Optimize marketing spend
4] Improve customer experience

## 📊 Dataset Information

### Dataset Source
1] **Type:** Synthetic dataset generated for demonstration
2] **Records:** 10,000 customers
3] **Features:** 17 columns
4] **File:** `customer_data.csv`

### Features Description

| Feature | Type | Description |
|---------|------|-------------|
| CustomerID | String | Unique customer identifier |
| Age | Integer | Customer age (18-65) |
| Gender | Categorical | Male / Female |
| Annual_Income | Integer | Yearly income ($20,000 - $150,000) |
| Num_Website_Visits | Integer | Website visits count |
| Time_Spent_Minutes | Integer | Time spent on site (5-120 mins) |
| Pages_Viewed | Integer | Number of pages viewed |
| Items_Viewed | Integer | Products viewed |
| Cart_Additions | Integer | Items added to cart |
| Previous_Purchases | Integer | Past purchase count |
| Days_Since_Last_Visit | Integer | Days since last visit |
| Discount_Sensitive | Binary | 0 or 1 |
| Device_Type | Categorical | Mobile / Desktop / Tablet |
| Browser | Categorical | Chrome / Firefox / Safari / Edge |
| Season | Categorical | Winter / Spring / Summer / Fall |
| Is_Weekend | Binary | 0 or 1 |
| Customer_Satisfaction | Integer | Rating 1-5 |
| **Purchase** | **Binary (Target)** | **0 = No, 1 = Yes** |
| Purchase_Amount | Integer | Amount spent (if purchased) |


## 🛠️ Technologies Used

### Programming & Environment
1] **Python 3.14.7**
2] **Jupyter Notebook** (via VS Code)
3] **Virtual Environment** (venv)

### Libraries
numpy - Numerical operations
pandas - Data manipulation
matplotlib - Basic visualization
seaborn - Statistical visualization
scikit-learn - Machine Learning
scipy - Statistical analysis
