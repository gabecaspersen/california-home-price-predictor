# 🏡 California Home Price Estimator

A machine learning project that predicts median housing prices across California districts based on demographic and geographic features.  

---

## 📖 Overview

This project builds a regression model to estimate home prices using the **California Housing Dataset**.  
It walks through a full data science workflow — from data exploration and preprocessing to model training, evaluation, and prediction.

---

## ⚙️ Features

- 🧹 **Data Cleaning & Feature Engineering**  
  Handles missing values, categorical encoding, and adds derived features such as:
  - `rooms_per_household`
  - `population_per_household`
  - `bedrooms_per_room`

- 🧠 **Model Training**  
  Trains and compares several regression models:
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  

- 📊 **Model Evaluation**  
  Evaluates model performance using:
  - RMSE (Root Mean Squared Error)
  - Cross-validation
  - Feature importance analysis

- 🗺️ **Visualization**  
  Includes geographic and correlation visualizations to understand patterns across California.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/california-home-price-estimator.git
cd california-home-price-estimator
