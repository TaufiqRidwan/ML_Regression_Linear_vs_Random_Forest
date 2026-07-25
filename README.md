# ML_Regression_Linear_vs_Random_Forest
Prediksi Harga Mobil dengan model ML Regression Linear dan Random Forest
Prediction Used Car Prices Using Linear Regression vs Random Forest Regression
Comparative Study of Linear Regression and Random Forest Regression for Used Car Price Prediction
Project Overview

This project develops a machine learning model to predict used car selling prices using historical vehicle transaction data. Two regression algorithms are compared:

Linear Regression
Random Forest Regression

The objective is to evaluate which model provides better predictive performance based on standard regression evaluation metrics.

The project follows a complete machine learning workflow, including:

Data Collection
Data Preprocessing
Exploratory Data Analysis (EDA)
Model Development
Model Evaluation
Price Prediction
Team Members
Name
M. Taufiq Ridwan
Darul Setiawan
Anang Santoso
Reza Fabian
Joko
Project Details
Title

Prediction Used Car Prices Using Linear Regression vs Random Forest Regression

Study Type

Comparative Machine Learning Study

Domain

Artificial Intelligence

Machine Learning

Automotive Data Analytics

Regression Analysis

Analysis Goals

The objectives of this project are:

Predict used car selling prices using machine learning.
Compare the performance of Linear Regression and Random Forest Regression.
Identify the most accurate regression model.
Analyze the influence of vehicle attributes on selling prices.
Demonstrate the application of supervised learning in automotive price prediction.
Dataset Information
Dataset

car_prices.csv

Source

Kaggle

Dataset Summary
Approximately 558,837 used car transaction records
16 variables
Large-scale real-world automotive sales dataset
Target Variable

sellingprice

Actual selling price of each vehicle.

Features
Feature	Description
year	Vehicle production year
make	Manufacturer
model	Vehicle model
trim	Vehicle trim
body	Vehicle body type
transmission	Transmission type
state	Sale location
condition	Vehicle condition score
odometer	Mileage
color	Exterior color
interior	Interior color
seller	Seller
mmr	Manheim Market Report value
saledate	Transaction date
Methodology
1. Data Preprocessing

The preprocessing stage includes:

Checking Missing Values
Checking Duplicate Records
Removing unnecessary columns
Selecting target variable
Encoding categorical features
Separating features and target
Train-Test Split
Numerical and categorical feature preparation
2. Exploratory Data Analysis (EDA)

Performed analyses include:

Descriptive Statistics
Selling Price Distribution
Odometer Distribution
Correlation Matrix
Selling Price by Production Year

EDA helps understand data characteristics before model development.

3. Machine Learning Models
Linear Regression

A statistical regression model that assumes a linear relationship between predictors and target.

Random Forest Regression

An ensemble learning algorithm based on multiple decision trees capable of modeling complex nonlinear relationships.

Model Evaluation Metrics

Three evaluation metrics are used:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Coefficient of Determination (R²)
Results
Linear Regression
Metric	Value
MAE	1038.61
RMSE	1620.51
R² Score	0.9711
Random Forest Regression
Metric	Value
MAE	918.88
RMSE	1522.03
R² Score	0.9745
Performance Comparison
Metric	Linear Regression	Random Forest
MAE	1038.61	918.88
RMSE	1620.51	1522.03
R²	0.9711	0.9745
Best Model

Random Forest Regression

The Random Forest model achieved:

Lower Mean Absolute Error
Lower Root Mean Squared Error
Higher R² Score

indicating better predictive accuracy than Linear Regression.

Prediction Example

Example input:

Feature	Value
Year	2020
Make	Toyota
Model	Corolla
Trim	LE
Body	Sedan
Transmission	Automatic
State	California
Condition	42
Odometer	35,000
Color	White
Interior	Black
Seller	Dealer
MMR	18,500
Predicted Selling Price

$19,128.50

Repository Structure
Prediction-Used-Car-Prices/
│
├── data/
│   └── car_prices.csv
│
├── notebooks/
│   └── ML_Regression_Linear_vs_Random_Forest.ipynb
│
├── images/
│   ├── EDA/
│   ├── LinearRegression/
│   ├── RandomForest/
│   └── Comparison/
│
├── presentation/
│   └── Prediction Used Car Prices Using Linear Regression vs Random Forest Regression.pdf
│
├── README.md
│
└── LICENSE
Technologies Used
Python
Google Colab
Pandas
NumPy
Matplotlib
Scikit-learn
Machine Learning Workflow
Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Linear Regression
      │
      ├──────────────┐
      ▼              ▼
Random Forest Regression
      │
      ▼
Model Evaluation
      │
      ▼
Performance Comparison
      │
      ▼
Used Car Price Prediction
Conclusion

This project demonstrates the application of supervised machine learning techniques for predicting used car prices using a large-scale automotive dataset. Both Linear Regression and Random Forest Regression achieved excellent predictive performance, with R² values above 97%.

Among the evaluated models, Random Forest Regression consistently outperformed Linear Regression by producing lower prediction errors (MAE and RMSE) and a higher coefficient of determination (R²). These results indicate that Random Forest Regression is more effective at capturing both linear and nonlinear relationships among vehicle attributes, making it the preferred model for used car price prediction.

Future Work

Potential improvements for future research include:

Advanced Feature Engineering
Hyperparameter Optimization
XGBoost Regression
LightGBM Regression
CatBoost Regression
Deep Learning Regression Models
Explainable AI (SHAP/LIME)
Web-Based Price Prediction Application
Real-Time Prediction System
Integration with Automotive Marketplace APIs
