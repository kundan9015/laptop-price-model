# Laptop Price Prediction using Polynomial Regression

This project demonstrates **polynomial regression** for predicting laptop prices based on CPU frequency.  
It focuses on understanding **non-linear relationships**, **overfitting behavior**, and **model evaluation** using standard regression metrics.

---

## 📌 Project Overview

- Implemented **Polynomial Regression** using both:
  - NumPy (`polyfit`, `poly1d`)
  - scikit-learn (`PolynomialFeatures`, `LinearRegression`)
- Compared different polynomial degrees
- Analyzed **overfitting and extrapolation issues**
- Evaluated model performance using **R² Score** and **Mean Squared Error (MSE)**

---

## 📂 Dataset

- **Feature (X):** CPU Frequency  
- **Target (y):** Laptop Price  

The dataset is used to study how price changes with CPU frequency and how polynomial degree impacts prediction stability.

---

## 🛠️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- scikit-learn  

---

## 📊 Key Concepts Covered

- Simple Linear Regression  
- Polynomial Regression  
- Polynomial Degree Selection  
- Overfitting vs Underfitting  
- Model Evaluation:
  - R² (Coefficient of Determination)
  - Mean Squared Error (MSE)
- Actual vs Predicted Distribution (KDE plots)

---

## 🔍 Model Evaluation

- **R² Score** is used to measure how well the model explains variance in data
- **MSE** is used to measure average prediction error
- Higher-degree polynomials show:
  - Better training fit
  - But unstable and unrealistic predictions (overfitting)

---

## 📈 Visualization

The notebook includes:
- Polynomial fit curves
- Degree-wise prediction comparison
- Actual vs Predicted price distribution plots

These visualizations help in understanding model behavior and performance.

---

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/USERNAME/laptop-price-model.git
