# ML_Regression_Linear_vs_Random_Forest
Prediksi Harga Mobil dengan model ML Regression Linear dan Random Forest
# 🚗 Prediction Used Car Prices Using Linear Regression vs Random Forest Regression

> Comparative Study of Linear Regression and Random Forest Regression for Used Car Price Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

This project aims to develop and compare two supervised machine learning algorithms for predicting **used car selling prices** using historical vehicle transaction data.

The comparison is conducted between:

- 📈 Linear Regression
- 🌲 Random Forest Regression

The project follows a complete machine learning workflow, from data preprocessing and exploratory data analysis (EDA) to model evaluation and price prediction.

---

## 👥 Team Members

| Name |
|------|
| **M. Taufiq Ridwan** |
| **Darul Setiawan** |
| **Anang Santoso** |
| **Reza Fabian** |
| **Joko** |

---

# 🎯 Objectives

This project aims to:

- Predict used car selling prices using machine learning.
- Compare Linear Regression and Random Forest Regression.
- Evaluate model performance using regression metrics.
- Identify the most influential variables affecting vehicle prices.
- Recommend the best model for used car price prediction.

---

# 📂 Dataset

**Dataset Name**

```
car_prices.csv
```

**Source**

Kaggle Used Car Auction Dataset

### Dataset Summary

| Item | Description |
|------|-------------|
| Records | ±558,837 |
| Features | 16 Variables |
| Target | sellingprice |
| Problem Type | Supervised Learning (Regression) |

---

## 📊 Features

| Feature | Description |
|----------|-------------|
| year | Production Year |
| make | Manufacturer |
| model | Vehicle Model |
| trim | Vehicle Variant |
| body | Body Type |
| transmission | Transmission Type |
| state | Sale Location |
| condition | Vehicle Condition |
| odometer | Mileage |
| color | Exterior Color |
| interior | Interior Color |
| seller | Seller |
| mmr | Manheim Market Report Value |
| saledate | Transaction Date |

---

# 🔬 Methodology

The project follows the CRISP-DM-inspired workflow below.

```text
Dataset
    │
    ▼
Data Preprocessing
    │
    ▼
Exploratory Data Analysis (EDA)
    │
    ▼
Feature Engineering
    │
    ▼
Linear Regression
    │
    ▼
Random Forest Regression
    │
    ▼
Model Evaluation
    │
    ▼
Performance Comparison
    │
    ▼
Price Prediction
```

---

## 🛠 Data Preprocessing

The preprocessing steps include:

- ✅ Check Missing Values
- ✅ Check Duplicate Data
- ✅ Remove Unnecessary Columns
- ✅ Define Target Variable
- ✅ Encode Categorical Features
- ✅ Feature & Target Separation
- ✅ Train-Test Split
- ✅ Numerical & Categorical Feature Processing

---

## 📈 Exploratory Data Analysis (EDA)

EDA includes:

- Descriptive Statistics
- Selling Price Distribution
- Odometer Distribution
- Correlation Matrix
- Selling Price by Production Year

---

# 🤖 Machine Learning Models

## 1️⃣ Linear Regression

Linear Regression is used as the baseline model to estimate vehicle prices assuming linear relationships among variables.

### Performance

| Metric | Value |
|---------|------:|
| MAE | **1038.61** |
| RMSE | **1620.51** |
| R² Score | **0.9711** |

---

## 2️⃣ Random Forest Regression

Random Forest Regression is an ensemble learning algorithm capable of capturing complex nonlinear relationships between vehicle features and selling prices.

### Performance

| Metric | Value |
|---------|------:|
| MAE | **918.88** |
| RMSE | **1522.03** |
| R² Score | **0.9745** |

---

# 📊 Model Comparison

| Metric | Linear Regression | Random Forest |
|---------|-----------------:|--------------:|
| MAE | 1038.61 | **918.88** ✅ |
| RMSE | 1620.51 | **1522.03** ✅ |
| R² Score | 0.9711 | **0.9745** ✅ |

### 🏆 Best Model

**Random Forest Regression**

Reasons:

- Lower MAE
- Lower RMSE
- Higher R² Score
- Better ability to model nonlinear relationships
- More accurate predictions for large datasets

---

# 🚘 Example Prediction

### Input

| Feature | Value |
|----------|------|
| Year | 2020 |
| Make | Toyota |
| Model | Corolla |
| Trim | LE |
| Body | Sedan |
| Transmission | Automatic |
| State | California |
| Condition | 42 |
| Odometer | 35,000 |
| Color | White |
| Interior | Black |
| Seller | Dealer |
| MMR | 18,500 |

### Predicted Selling Price

```text
Estimated Selling Price

$19,128.50
```

---

# 📁 Repository Structure

```text
Prediction-Used-Car-Prices/
│
├── data/
│   └── car_prices.csv
│
├── notebooks/
│   └── ML_Regression_Linear_vs_Random_Forest.ipynb
│
├── images/
│   ├── cover.png
│   ├── preprocessing.png
│   ├── eda.png
│   ├── linear_regression.png
│   ├── random_forest.png
│   ├── comparison.png
│   └── prediction.png
│
├── presentation/
│   └── Prediction Used Car Prices Using Linear Regression vs Random Forest Regression.pdf
│
├── README.md
│
└── LICENSE
```

---

# 💻 Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# 📐 Evaluation Metrics

Three regression metrics were used:

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **Coefficient of Determination (R² Score)**

---

# ✅ Conclusion

This study demonstrates that both Linear Regression and Random Forest Regression achieve excellent predictive performance for used car price estimation.

However, **Random Forest Regression** consistently outperformed Linear Regression by producing:

- Lower Mean Absolute Error (MAE)
- Lower Root Mean Squared Error (RMSE)
- Higher R² Score

These results indicate that Random Forest Regression is more effective in modeling both linear and nonlinear relationships among vehicle characteristics, making it the preferred model for used car price prediction.

---

# 🚀 Future Work

Potential improvements include:

- Feature Engineering Optimization
- Hyperparameter Tuning
- XGBoost Regression
- LightGBM
- CatBoost
- Deep Learning Regression
- Explainable AI (SHAP & LIME)
- Web-Based Price Prediction System
- Real-Time Prediction API

---

# 📄 License

This project is intended for **educational and research purposes**.

---

## ⭐ If you find this project useful, consider giving it a star on GitHub!
