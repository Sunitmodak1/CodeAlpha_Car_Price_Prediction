# Car Price Prediction 🚗💰

This project is part of my **Data Science Internship** at **CodeAlpha**. The goal was to build a machine learning model that can predict the selling price of used cars based on various features such as the car's age, mileage, fuel type, and transmission.

## 📌 Project Overview
* **Student ID:** CA/DF1/22584
* **Internship Domain:** Data Science
* **Project Name:** Car Price Prediction
* **Organization:** CodeAlpha

## 📂 Dataset
The dataset used for this project contains information about used cars, including:
* **Car Name:** The brand and model of the car.
* **Year:** The year the car was purchased.
* **Selling Price:** The target variable we are predicting.
* **Present Price:** The current showroom price of the car.
* **Kms Driven:** The total distance driven by the car.
* **Fuel Type:** Petrol, Diesel, or CNG.
* **Seller Type:** Dealer or Individual.
* **Transmission:** Manual or Automatic.
* **Owner:** The number of previous owners.

## 🛠️ Technologies Used
* **Python** (Programming Language)
* **Pandas** (Data Manipulation)
* **Matplotlib & Seaborn** (Data Visualization)
* **Scikit-Learn** (Machine Learning Library)
* **Linear Regression** (Baseline Model)
* **Random Forest Regressor** (Final Model)
* **Google Colab / Jupyter Notebook** (IDE)

## 🚀 Key Features
1.  **Data Preprocessing:** Handled categorical variables (Fuel Type, Transmission, etc.) using One-Hot Encoding and Standard Scaling within a Pipeline.
2.  **Model Comparison:** Trained both **Linear Regression** and **Random Forest Regressor** to find the best performance.
3.  **High Accuracy:** The Random Forest model achieved an outstanding **R² Score of 0.96 (96%)**.
4.  **Feature Importance:** Analyzed which factors (like Present Price and Year) influence the car price the most.
5.  **Interactive Prediction:** Includes a user-input system to predict prices for new cars.

## 📊 Results
* **Linear Regression R²:** 0.85
* **Random Forest R²:** 0.96 (Selected Best Model)

### 📷 Actual vs Predicted Prices
The model shows a nearly perfect correlation between predicted and actual prices.
![Actual vs Predicted](car.png)

### 📷 Feature Importance
This chart shows that **"Present Price"** is the most important factor in determining the selling price.
![Feature Importance](car2.png)

## 🤝 Acknowledgement
Thanks to **@CodeAlpha** for providing this opportunity to work on real-world regression problems.

---
**Author:** Sunit Modak
**LinkedIn:** [https://www.linkedin.com/in/sunit-modak-6064403a5/](https://www.linkedin.com/in/sunit-modak-6064403a5/)
