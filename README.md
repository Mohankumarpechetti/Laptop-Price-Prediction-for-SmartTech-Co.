# 💻 Laptop Price Prediction - Capstone Project (OdinSchool)

A machine learning project aimed at predicting the prices of laptops based on their specifications such as brand, CPU, GPU, display, RAM, and storage. Built as a capstone project for OdinSchool’s Data Science program, this model helps SmartTech Co. optimize pricing strategies and gain insights into market trends.

---

## 📌 Project Objective

SmartTech Co. partnered with us to:

- Predict laptop prices accurately using historical data.
- Identify key features influencing laptop prices.
- Assist in competitive pricing and market positioning strategies.
- Handle new, unseen laptop data for real-time predictions.

---

## 🧠 Machine Learning Pipeline

1. **Data Cleaning**: 
   - Handled missing values and outliers.
   - Standardized units (e.g., weight in kg, RAM in GB).

2. **Feature Engineering**:
   - Extracted CPU brand, GPU brand, PPI, resolution, and more.
   - Binary flags for Touchscreen, IPS display, SSD, etc.

3. **Preprocessing**:
   - One-hot encoding for categorical variables.
   - Feature scaling with `StandardScaler`.

4. **Model Training**:
   - Multiple models trained: Linear Regression, SVR, Decision Tree, Random Forest, Gradient Boosting.
   - Final model: **Gradient Boosting Regressor** selected based on R² and RMSE.

5. **Evaluation**:
   - Achieved **R² Score of 0.82** on test data.
   - Visualized actual vs predicted prices.

6. **Deployment Readiness**:
   - Supports real-time prediction on new laptops with the same feature format.
   - Model and pipeline saved using `joblib`.

---

## 🏆 Final Model Performance

| Metric         | Value      |
|----------------|------------|
| MAE            | ~9952.46   |
| RMSE           | ~13957.65  |
| R² Score       | ~0.82      |

---

## 📁 Project Structure

