# 🏠 House Price Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📖 Overview

This project aims to predict house prices using Machine Learning techniques based on property characteristics such as house quality, living area, garage size, basement area, and construction year.

The project covers the complete Machine Learning pipeline, including:

✅ Data Cleaning
✅ Exploratory Data Analysis (EDA)
✅ Feature Engineering
✅ Feature Scaling
✅ Model Training
✅ Cross Validation
✅ Model Evaluation
✅ Business Insights

---

## 🎯 Objectives

The main goals of this project are:

* Predict residential property prices accurately.
* Identify factors that significantly influence house prices.
* Build a regression model that can support real-estate valuation decisions.
* Generate business insights from housing market data.

---

## 📂 Dataset Features

The dataset includes several important property attributes:

| Feature      | Description                         |
| ------------ | ----------------------------------- |
| OverallQual  | Overall material and finish quality |
| GrLivArea    | Above-ground living area            |
| GarageCars   | Garage capacity                     |
| GarageArea   | Garage size                         |
| TotalBsmtSF  | Basement area                       |
| FullBath     | Number of bathrooms                 |
| TotRmsAbvGrd | Total rooms above ground            |
| YearBuilt    | Construction year                   |
| YearRemodAdd | Renovation year                     |
| LotArea      | Property lot size                   |
| Fireplaces   | Number of fireplaces                |

🎯 **Target Variable:** SalePrice

---

## 🔄 Machine Learning Workflow

### 📌 1. Data Understanding

* Dataset exploration
* Data type inspection
* Missing value detection
* Duplicate checking

### 📌 2. Data Preprocessing

* Missing value imputation
* Outlier removal using IQR
* Feature selection

### 📌 3. Exploratory Data Analysis

* Price distribution analysis
* Correlation analysis
* Feature relationship visualization

### 📌 4. Feature Engineering

* Log Transformation
* Feature Scaling with StandardScaler

### 📌 5. Model Development

* Linear Regression

### 📌 6. Model Evaluation

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score
* Cross Validation

---

## 📊 Model Performance

| Metric   | Score  |
| -------- | ------ |
| MAE      | 15,865 |
| RMSE     | 21,402 |
| R² Score | 0.8560 |

### 🔍 Interpretation

* The model explains approximately **85.6%** of house price variability.
* Prediction errors remain relatively low.
* The model demonstrates strong predictive performance for housing price estimation.

---

## 📈 Visualizations

### House Price Distribution

* Distribution before transformation
* Distribution after log transformation

### Correlation Analysis

* Heatmap of feature relationships

### Model Evaluation

* Actual vs Predicted Prices
* Residual Analysis

---

## 💡 Business Insights

### 🏆 Overall Quality Drives Price

Properties with higher quality scores consistently achieve higher market values.

### 📏 Larger Living Areas Increase Value

Living area is one of the strongest predictors of house price.

### 🚗 Garage Capacity Matters

Homes with larger garages tend to attract more buyers and command premium prices.

### 🏡 Newer Houses Sell Higher

Recently built or renovated properties generally have higher selling prices.

### 🏠 Basement Space Adds Value

Finished basements contribute positively to property valuation.

### 🌳 Lot Size Still Matters

Larger land areas remain an important factor in determining market price.

---

## 🛠️ Technologies Used

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy
* 📈 Matplotlib
* 🎨 Seaborn
* 🤖 Scikit-Learn
* 📓 Jupyter Notebook

---

## 🚀 Installation

```bash
git clone https://github.com/yourusername/house-price-prediction-linear-regression.git

cd house-price-prediction-linear-regression

pip install -r requirements.txt
```

---

## 🔮 Future Improvements

* 🌲 Random Forest Regressor
* ⚡ XGBoost Regressor
* 🚀 LightGBM Regressor
* 🎯 Hyperparameter Tuning
* 🌐 Streamlit Deployment
* ☁️ Cloud Deployment

---

## 👨‍💻 Author

**Briliant Vilendro Kastilong**

🎓 Computer Science Student
📊 Data Science Enthusiast
🤖 Machine Learning Practitioner
💻 Front-End Developer

---

⭐ If you find this project useful, don't forget to give it a star!
