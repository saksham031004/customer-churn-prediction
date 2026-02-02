# customer-churn-prediction
# 🧠 Customer Churn Prediction Machine Learning Project

This repository contains an end‑to‑end **Customer Churn Prediction** project built with Python. It includes Exploratory Data Analysis (EDA), model building, and a Flask API for deployment.
This project focuses on building an end-to-end Customer Churn Prediction system using machine learning. The objective is to analyze customer behavior data and predict whether a customer is likely to leave a telecom service. The project covers the complete data science lifecycle, including Exploratory Data Analysis (EDA), data preprocessing, model training and evaluation, and deployment using a Flask web application. The trained model is integrated into a user-friendly interface that allows real-time churn prediction based on customer inputs, helping businesses make data-driven retention decisions.
👉 The goal of this project is to analyze customer behavior and build a machine learning model that predicts whether customers are likely to churn (leave a service). This is useful for businesses aiming to retain customers and reduce churn rates.

---

## 📌 Table of Contents

1. [Project Overview](#project-overview)  
2. [Key Features](#key-features)  
3. [Folder Structure](#folder-structure)  
4. [Getting Started](#getting-started)  
5. [Usage](#usage)  
6. [Dependencies](#dependencies)  
7. [Contributing](#contributing)  
8. [License](#license)

---

## 📍 Project Overview

Customer churn refers to the situation where customers stop using a company's service. Predicting churn helps businesses take proactive steps to retain customers.

In this project, you will find:
- Data Exploration  
- Model Training & Evaluation  
- Flask app for real-time prediction

We perform full lifecycle workflows from data understanding to model deployment. :contentReference[oaicite:2]{index=2}

---

## 🚀 Key Features

✔ End-to-end **Exploratory Data Analysis** (EDA)  
✔ Machine Learning **Model Building**  
✔ **Flask API** for deployment and prediction  
✔ Customer churn model saved as `.sav` file  
✔ Simple frontend for user input and churn prediction

---

## 📁 Folder Structure

📦 MLProject-ChurnPrediction
┣ 📂 src
┣ 📜 Churn Analysis - EDA.ipynb
┣ 📜 Churn Analysis - Model Building.ipynb
┣ 📜 Exploratory Data Analysis -saksham wadhwa.pdf
┣ 📜 WA_Fn-UseC_-Telco-Customer-Churn.csv
┣ 📜 app.py
┣ 📜 model.sav

📊 What’s Inside
🔹 Exploratory Data Analysis (EDA)

The EDA notebook explores patterns and relationships in the customer dataset. It helps understand which factors influence churn.

🔹 Model Building

The Model Building notebook includes:

Data preprocessing

Model selection

Training and evaluation

Saving trained model as model.sav

🔹 Flask Deployment

app.py loads the saved model and serves a web form to enter customer info and see churn results.

📦 Dependencies

Here are core Python libraries used:

Purpose	Libraries
Data handling	pandas, numpy
Modeling	scikit-learn
Deployment	Flask, joblib

You can install them with:

pip install pandas numpy scikit-learn Flask joblib

🤝 Contributing

Feel free to fork this repo and submit pull requests to improve the project! Whether it's updating documentation, adding tests, or enhancing features — contributions are welcome.
