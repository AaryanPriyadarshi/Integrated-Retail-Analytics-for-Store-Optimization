# Integrated-Retail-Analytics-for-Store-Optimization
Retail sales forecasting using machine learning with sales, stores, and external features. Includes EDA, hypothesis testing, preprocessing, and models (Random Forest, XGBoost). XGBoost outperforms, with holidays, promotions, and store size as key sales drivers.
# 🛒 Retail Sales Forecasting using Machine Learning  

## Project Overview  
This project focuses on predicting **weekly retail sales** using multi-source data.  
The goal is to integrate sales, store, and external features, explore seasonal trends, validate assumptions with hypothesis testing, and build ML models to optimize store performance.  

---

## Key Features  
- **Data Integration:** Combined sales, store info, and external features (fuel, CPI, unemployment, promotions).  
- **Exploratory Data Analysis (EDA):**  
  - Seasonal trends in sales  
  - Holiday vs non-holiday performance  
  - Store type comparisons  
  - Correlation heatmaps  
  - Monthly sales distribution  
- **Hypothesis Testing:** Verified whether holiday weeks significantly increase sales.  
- **Preprocessing:**  
  - Label encoding for categorical variables  
  - Time-based feature engineering (Month, Quarter, Week)  
  - StandardScaler normalization  
- **Machine Learning Models:**  
  - Random Forest Regressor  
  - XGBoost Regressor  
- **Evaluation:**  
  - Metrics: RMSE, MAE, R²  
  - Performance comparison table + bar chart  
- **Feature Importance:**  
  - Key drivers: Holidays, Store Size, Promotions, Economic Indicators  

---

## Project Structure  
├── sales data-set.csv # Sales dataset
├── stores data-set.csv # Store metadata
├── Features data set.csv # External features dataset
├── RetailSales_EDA.ipynb # Colab notebook (EDA + ML)
├── README.md # Project description
