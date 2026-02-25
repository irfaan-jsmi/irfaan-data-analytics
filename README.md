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



# 📊 Customer Segmentation Analysis

## 📌 Project Description

This project focuses on performing Customer Segmentation Analysis for an e-commerce company.  
The goal is to analyze customer purchasing behavior and divide customers into distinct segments using clustering techniques.

Customer segmentation helps businesses:
- Improve targeted marketing strategies
- Increase customer satisfaction
- Enhance business decision-making
- Boost revenue growth

---

## 🎯 Objectives

- Perform Data Cleaning and Exploration
- Analyze customer purchase patterns
- Apply K-Means Clustering algorithm
- Visualize customer segments
- Generate actionable business insights

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset Information

The dataset includes the following features:

- Customer ID
- Age
- Gender
- Annual Income
- Spending Score
- Purchase Frequency
- Total Purchase Amount

---

## 🔍 Project Workflow

### 1️⃣ Data Collection
Loaded the dataset using Pandas.

### 2️⃣ Data Cleaning
- Checked for missing values
- Removed duplicate records
- Handled inconsistent data entries

### 3️⃣ Exploratory Data Analysis (EDA)
- Generated statistical summary
- Analyzed income and spending distributions
- Identified patterns in customer behavior

### 4️⃣ Feature Scaling
Used StandardScaler to normalize numerical features before clustering.

### 5️⃣ K-Means Clustering
Applied K-Means algorithm to segment customers into different clusters.

### 6️⃣ Data Visualization
Created scatter plots and visual representations to interpret clusters.

---

## 📊 Results

The clustering model identified distinct customer segments such as:

- High Income – High Spending (Premium Customers)
- Low Income – Low Spending (Budget Customers)
- High Income – Low Spending (Potential Customers)
- Low Income – High Spending (Impulse Buyers)

---

## 💡 Business Insights

- Premium customers can be targeted with exclusive offers.
- Potential customers can be converted using personalized marketing campaigns.
- Budget customers may respond well to discounts and promotional offers.
- Loyalty programs can retain high-value customers.

---

## 🎓 Learning Outcomes

- Practical understanding of clustering algorithms
- Data preprocessing and feature scaling techniques
- Exploratory Data Analysis skills
- Business-oriented data interpretation
- Data visualization techniques

---

## 🚀 Future Improvements

- Implement RFM (Recency, Frequency, Monetary) Analysis
- Apply Hierarchical Clustering
- Build a customer recommendation system
- Deploy the project using Streamlit or Flask

---

## 📈 Results

The Linear Regression model was successfully trained and tested.  
The evaluation metrics show the model’s effectiveness in predicting housing prices.



# 🍷 Wine Quality Prediction

## 📌 Project Overview
This project focuses on predicting the quality of wine based on its chemical properties using Machine Learning techniques. The goal is to build classification models that can determine wine quality using features such as acidity, density, alcohol content, and other chemical attributes.

## 🎯 Objective
To analyze wine chemical characteristics and build predictive models using:
- Random Forest
- Stochastic Gradient Descent (SGD)
- Support Vector Classifier (SVC)

## 📂 Dataset
The dataset contains physicochemical properties of wine samples and their quality ratings.

Features include:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (Target Variable)

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🔍 Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Data Visualization
5. Feature Selection
6. Model Training
7. Model Evaluation
8. Accuracy Comparison

## 🤖 Models Used

- Random Forest Classifier
- Stochastic Gradient Descent Classifier
- Support Vector Classifier (SVC)

## 📊 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

## 🚀 Results
The models were trained and evaluated to determine which algorithm performs best in predicting wine quality.

## 📈 Conclusion
Machine learning models can effectively predict wine quality using chemical attributes. Random Forest generally performs better due to its ensemble learning capability.
