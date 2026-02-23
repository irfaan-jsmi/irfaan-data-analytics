# Exploratory Data Analysis (EDA) on Retail Sales Data

## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on a retail sales dataset to uncover meaningful patterns, trends, and insights that can help businesses make data-driven decisions.

The analysis includes data cleaning, descriptive statistics, time series analysis, customer and product analysis, data visualization, and actionable business recommendations.

---

## 🎯 Objectives
- Understand customer purchasing behavior
- Analyze sales trends over time
- Identify high-performing product categories
- Explore customer demographics and payment preferences
- Provide actionable recommendations for business growth

---

## 📂 Dataset Description
The dataset contains **99,457 retail transactions** with the following attributes:

| Column Name | Description |
|------------|------------|
| invoice_no | Unique invoice number |
| customer_id | Unique customer identifier |
| gender | Customer gender |
| age | Customer age |
| category | Product category |
| quantity | Number of items purchased |
| price | Total purchase amount |
| payment_method | Payment type (Cash / Credit Card / Debit Card) |
| invoice_date | Date of purchase |
| shopping_mall | Shopping mall name |

---

## 🛠️ Tools & Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Steps Performed

### 1. Data Loading & Cleaning
- Loaded dataset using Pandas
- Checked for missing values and duplicates
- Converted date column into datetime format

### 2. Descriptive Statistics
- Calculated mean, median, mode, and standard deviation
- Analyzed age, quantity, and price distributions

### 3. Time Series Analysis
- Analyzed monthly sales trends
- Identified seasonal patterns in customer spending

### 4. Customer & Product Analysis
- Sales distribution by gender
- Category-wise sales performance
- Payment method analysis
- Top-performing shopping malls

### 5. Data Visualization
- Bar charts
- Line charts
- Pie charts
- Heatmap for category vs gender analysis

### 6. Business Recommendations
- Focus on high-revenue product categories
- Target marketing campaigns based on seasonal trends
- Improve performance of low-performing shopping malls
- Promote preferred payment methods for better conversions

---

## 📊 Key Insights
- Clothing and Shoes categories contribute the highest sales
- Female customers show a higher contribution to total revenue
- Credit Card is the most preferred payment method
- Sales exhibit clear seasonal patterns

---

## 📁 Project Structure



# 🏠 Housing Price Prediction using Linear Regression

## 📌 Project Overview

This project aims to predict housing prices using **Linear Regression**, a supervised machine learning algorithm.  
It demonstrates the complete machine learning workflow including data preprocessing, model training, evaluation, and prediction.

---

## 🎯 Objective

To build a regression model that can accurately predict house prices based on various features in the dataset.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

---

## 📊 Workflow

### 1️⃣ Data Loading
- Imported required libraries
- Loaded the housing dataset using Pandas

### 2️⃣ Data Preprocessing
- Checked for missing values
- Cleaned and prepared the dataset
- Selected feature variables (X) and target variable (y)

### 3️⃣ Exploratory Data Analysis (EDA)
- Visualized relationships between features
- Analyzed correlation between variables
- Identified important factors affecting house prices

### 4️⃣ Model Building
- Split dataset into training and testing sets
- Applied Linear Regression model
- Trained the model using training data

### 5️⃣ Model Evaluation
- Predicted house prices on test data
- Evaluated performance using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

---

## 📈 Results

The Linear Regression model was successfully trained and tested.  
The evaluation metrics show the model’s effectiveness in predicting housing prices.
