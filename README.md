# Predicting Delivery Delays with Machine Learning 🚚⏱️
This project is part of the Final Project of the Data Science Program at Dibimbing.id. The objective is to predict whether a shipment will be delayed or not using machine learning techniques, and to understand what factors contribute most to these delays.
## 🧠 Business Understanding
An e-commerce company wants to proactively mitigate delivery delays. Two key questions addressed:
1. Which features most influence whether a delivery is delayed?
2. Can we build a predictive model to anticipate delays?
## 📦 Dataset Overview
The dataset includes:
* Shipping details (warehouse block, mode of shipment, weight)
* Customer information (gender, care calls, prior purchases, rating)
* Product details (cost, importance, discount)
* Target variable: Reached on time (1: Yes, 0: No)

Source:[ Kaggle - E-commerce Shipping Data](https://www.kaggle.com/datasets/prachi13/customer-analytics?resource=download)
## 🔎 EDA Highlights
* Warehouse B has the highest percentage of delays.
* Road is the most reliable shipment method.
* Heavier and more expensive items tend to arrive faster.
* Frequent buyers generally experience fewer delays.
## ⚙️ Workflow
1. Data preprocessing
2. Exploratory Data Analysis (EDA)
3. Model building using:
   * Logistic Regression
   * Decision Tree
   * Random Forest
   * XGBoost
   * LightGBM
5. Evaluation using F1 Score
6. Feature importance analysis with SHAP
## 🏆 Best Model
Decision Tree was selected for its stable performance on both training and testing sets (F1 Score ≈ 71%).
## 🔍 Top Influential Features
1. Weight – Heavier items are prioritized.
2. Cost after Discount – Higher-cost items get faster treatment.
3. Prior Purchases – Loyal customers often experience better delivery outcomes.
## 📈 Recommendations
1. Include additional features like location, travel distance, and time of order.
2. Prioritize smaller and low-cost items to reduce delays.
3. Avoid overlapping discount periods with peak shipping times.
## 📎 Attachments
* 📊 [Google Slides Presentation](https://docs.google.com/presentation/d/1WDKRAyOLgI6VJUYmbScxIinyG2YvWi3s/edit?usp=sharing&ouid=108909113527976904684&rtpof=true&sd=true)
* 🧪 [Google Colab Notebook](https://colab.research.google.com/drive/1Tinc4vawqzsCU_pyUdoM0mXPhMlSjPzI?usp=sharing)
