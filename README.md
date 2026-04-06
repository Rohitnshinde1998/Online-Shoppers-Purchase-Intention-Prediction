# 🛒 Online Shoppers Purchase Intention Prediction
## 📌 One-Line Summary
A machine learning project to predict whether a website visitor will make a purchase based on their browsing behavior.

## 📖 Overview
This project analyzes user behavior on an e-commerce website and builds a machine learning model to predict purchase intention. It helps businesses identify potential buyers and improve conversion rates.

## 📊 Dataset
Source: UCI Machine Learning Repository

Contains user session data such as:
Page visits

Time spent

Bounce & exit rates

Traffic source & visitor type

Target Variable: Revenue (0 = Non-Buyer, 1 = Buyer)

## 🛠️ Tools and Technologies
Python 🐍

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

## ⚙️ Methods
Data Cleaning & Preprocessing

Feature Engineering (Label Encoding)

Exploratory Data Analysis (EDA)

Feature Scaling

Model Building:
Logistic Regression
Random Forest
XGBoost
Model Evaluation:
Accuracy
Precision, Recall
ROC-AUC Score
Confusion Matrix

## 🔍 Key Insights
PageValues is the strongest predictor of purchase
Higher engagement → higher purchase probability
High bounce & exit rates → low conversion
Returning users are more likely to buy
Most users are non-buyers (class imbalance)

## 📈 Dashboard / Model Output
Best Model: Random Forest
Accuracy: ~91%
ROC-AUC Score: ~0.92

Confusion Matrix:

2708 Non-buyers correctly predicted
312 Buyers correctly predicted
203 Buyers missed

## ✅ Result & Conclusion

This project demonstrates how machine learning can effectively predict customer purchase behavior.
By identifying high-intent users, businesses can improve targeting, reduce drop-offs, and increase revenue.

## 👨‍💻 Author & Contact

Rohit Namdev Shinde
📧 Email: rohitnshinde1998@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/rohit-shinde-aa24a7392/
