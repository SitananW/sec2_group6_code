# sec2_group6_code  
**ITCS 227 – Introduction to Data Science | Mahidol University 2026**

---

## 📖 Project Overview
This project provides a comprehensive analysis of **fashion trends and consumer shopping patterns** using multiple data science techniques.  
The analysis examines:
- Seasonal demand  
- Demographic preferences  
- Time series forecasting  
- Google Trends correlation  
- Cross-dataset validation  

---

## 📂 Project Structure

### 🔬 Notebooks
- **`fashion_analysis.ipynb` – Exploratory Data Analysis**
  - Seasonal demand patterns  
  - Gender and age group preferences  
  - Sales trends by product category  
  - **Key finding:** Winter shows highest demand; Shirts are top performers  

- **`timeseries_forecasting.ipynb` – Time Series Modeling**
  - ARIMA and SARIMA models  
  - Seasonal decomposition  
  - Sales forecasts with confidence intervals  
  - Model diagnostics and validation  

- **`google_trends_analysis.ipynb` – Market Trend Analysis**
  - Google Trends search volume tracking  
  - Correlation between online interest and actual sales  
  - Brand positioning insights  

- **`cross_validation.ipynb` – Cross-Dataset Validation**
  - Comparison with Kaggle Customer Shopping Trends dataset  
  - Statistical correlation analysis (Pearson r)  
  - Regional pattern differences  

### 📊 Data Files
- `fashion_new_data2.xlsx` – Main dataset (2,640 records, 2018–2025)  
- `shopping_trends.csv` – Kaggle customer data (3,900 records)  
- `zara_trends_combined.csv` – Google Trends data  

---

## 🔍 Key Features
- **Exploratory Data Analysis**
  - Seasonal demand heatmaps (Season × Product)  
  - Gender-based product preferences  
  - Age group purchasing patterns  
  - Sales distribution across categories  

- **Time Series Forecasting**
  - ARIMA/SARIMA modeling with seasonal patterns  
  - Multi-step ahead predictions  
  - Model diagnostics (ACF, PACF, residual analysis)  

- **Cross-Dataset Validation**
  - 8 shared product categories across datasets  
  - Pearson correlation analysis (r = -0.20, weak alignment)  
  - Regional fashion preference differences (Europe/Asia vs US)  

- **Visualizations**
  - Heatmaps (Season × Category, Season × Gender)  
  - Bar charts and line plots  
  - Time series forecasts with confidence bands  
  - Correlation matrices  

---

## 📊 Main Findings

| Finding          | Detail |
|------------------|--------|
| **Seasonal Peak** | Winter season dominates sales volume |
| **Top Product**   | Shirts lead across demographics |
| **Gender Trend**  | Female/Male preferences vary by category |
| **Age Pattern**   | 35–45 age group has highest sales |
| **Regional Gap**  | ZARA (Europe/Asia) vs Kaggle (US): weak correlation |
| **Forecast Accuracy** | SARIMA captures seasonality effectively |

---

## 🛠️ Requirements
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scipy  
- scikit-learn  
- statsmodels  
- openpyxl  
