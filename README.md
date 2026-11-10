# Price Prediction of Grocery Using Machine Learning Techniques

## 🎓 Academic Research Overview
This repository contains the source code, data preprocessing pipelines, and empirical model evaluations executed as part of my Postgraduate Applied Research Thesis framework under the European Higher Education Area (EHEA) standards at Dublin Business School, Ireland.

The research investigates the structural applicability and asymptotic efficiency of supervised machine learning architectures to systematically forecast retail grocery pricing configurations by parsing volatile multi-factor variables.

## 📊 Dataset & Features
The model operates on a processed high-dimensional matrix consisting of **17,259 records** across structural market columns:
- `Item Categories` (e.g., Fresh Vegetables, Fresh Fruits, Beverages, Bakery)
- `Current Price` & `Previous Price` (Stochastic market markers)
- `Amount` & `Units` (Volumetric structural parameters)

## 🛠️ Computational Framework & Model Performance
The empirical study evaluates the predictive efficiency across four core regression models utilizing standard error metrics: Mean Squared Error (**MSE**), Mean Absolute Error (**MAE**), Coefficient of Determination (**R²**), and Explained Variance Score (**EVS**).

### Empirical Results Summary:
*   **Linear Regression (Optimal Model):** MSE: `124.58` | MAE: `0.6411` | R²: `0.4882` | EVS: `0.4886`
*   **Gradient Boosting Regressor:** MSE: `153.24` | MAE: `3.0949` | R²: `0.3705`
*   **Random Forest Regressor:** MSE: `154.36` | MAE: `0.9506` | R²: `0.3659`
*   **Support Vector Regressor (SVR):** MSE: `219.75` | MAE: `1.6637` | R²: `0.0973`

## 🗂️ Core Repository Files
- `Abhinav_ML.ipynb`: Comprehensive Google Colab / Jupyter Notebook containing the structural exploratory data analysis (EDA), data imputation loops, multi-variable boxplot distribution outlier removal pipelines, and training/testing matrix validation routines.
- `products_data.csv`: Cleaned post-graduate validation dataset.

---
**Author:** Abhinav Singh Voria  
**Degree Track:** MSc in Business Analytics (Class of 2024)  
**Professional Domain:** Senior Software Engineer (16 Years Enterprise Track)
