# 📦 LR_Delivery_Time_Prediction

**Author**: Ankit Ranjan  
**Assignment**: Parcel Delivery Time Estimation using Linear Regression    
**Date**: July 2025  

---

## 📘 Project Overview

This project aims to estimate parcel delivery times using linear regression techniques, based on operational data provided by Porter. The goal is to not only build an accurate predictive model but also generate actionable business insights for optimizing delivery performance.

---

## 📂 Files Included

| File Name                                         | Description                                                                 |
|--------------------------------------------------|-----------------------------------------------------------------------------|
| `LR_Delivery_Time_Prediction_AnkitRanjan.ipynb`  | Jupyter Notebook with complete code, visualizations, and explanations      |
| `LR_Delivery_Time_Prediction_AnkitRanjan.pdf`    | Report detailing methodology, analysis, and conclusions                    |
| `LR_Delivery_Time_Prediction_AnkitRanjan.zip`    | Zipped folder containing the above two files for submission                |

---

## 🔧 Technologies Used

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

---

## 🔍 Key Tasks

### 1. Data Preprocessing
- Converted timestamps to datetime
- Engineered new features like `delivery_time`, `order_hour`, and `isWeekend`
- Converted categorical variables appropriately
- Handled missing values and applied IQR capping for outliers

### 2. Exploratory Data Analysis
- Visualized distributions of numerical and categorical variables
- Assessed feature-target relationships using scatter plots and box plots
- Used correlation heatmap to identify relevant features

### 3. Model Building
- Applied Linear Regression with and without feature selection
- Used Recursive Feature Elimination (RFE) to choose top 8 predictors
- Evaluated model using R², MSE, and residual plots

---

## 📈 Results

- **Final R² Score**: 0.8636  
- **MSE**: 11.94  
- Most important predictors: `total_outstanding_orders`, `distance`, `order_hour`, `isWeekend`

---

## 💡 Business Insights

- Orders with higher `total_outstanding_orders` tend to have longer delivery times.
- Adding more dashers during peak times reduces delivery delay.
- Weekend and order protocol significantly affect delivery time.

---

## 📌 Assumptions

- Delivery time is computed as the time difference (in minutes) between `created_at` and `actual_delivery_time`.
- Categorical columns were encoded only after datatype conversion and validation.
- Outliers were capped using the IQR method, not removed.

---

## 📝 Submission Guidelines

This GitHub repository includes:
- 📓 The Jupyter Notebook (`.ipynb`)
- 📄 The Final Report (`.pdf`)
- 📦 A ZIP file containing both of the above


---

## 📬 Contact

For queries or feedback, contact: [ankit0ranjan@gmail.com]  
Or message me via [GitHub Profile](https://github.com/ankit-ranjan-neu)

---
