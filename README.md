# 📄 Retail Sales Trend & Seasonality Analysis

## 📘 Project Title
Retail Sales Trend & Seasonality Analysis

---

## 📌 Overview
This project performs a complete time-series statistical analysis on retail sales data obtained from Kaggle.  
The goal is to understand:

- Long-term sales **trend**
- Recurring **seasonality**
- Degree of **autocorrelation**
- Amount of **random noise**
- Whether the series is **stationary** (critical for forecasting)

This prepares the dataset for future forecasting using models such as ARIMA, SARIMA, or machine learning methods.

---

## 🧩 Problem Statement
Retail sales fluctuate due to weekends, festivals, promotions, seasonal buying habits, and external factors.  
Management needs clarity on:

- Whether sales exhibit an upward or downward **trend**
- Presence and strength of **seasonal effects**
- Levels of **randomness/noise**
- Whether the data satisfies **stationarity assumptions**

Without analyzing these characteristics, forecasting accuracy may suffer.

---

## 🎯 Project Objectives
This project includes:

✔ Creating a DATE column from YEAR + MONTH  
✔ Aggregating sales to monthly level  
✔ Plotting sales trend  
✔ Performing Seasonal Decomposition (Trend, Seasonal, Residual)  
✔ ACF & PACF plots for autocorrelation  
✔ ADF Test for stationarity  
✔ Preparing dataset for forecasting models  

---

## 🛠 Technologies Used
- **Python 3.x**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Statsmodels**
- **Jupyter Notebook**

---

## 📂 Dataset Description

YEAR
MONTH
SUPPLIER
ITEM CODE
ITEM DESCRIPTION
ITEM TYPE
RETAIL SALES
RETAIL TRANSFERS
WAREHOUSE SALES


The project constructs a time-series index from YEAR and MONTH and aggregates monthly metrics.

---

## 📜 How to Run the Code

The notebook is organized into separate cells:

1. Import Libraries  
2. Load Dataset  
3. Aggregate Monthly Data  
4. Plot Retail Sales Trend  
5. Seasonal Decomposition  
6. ACF & PACF Plots  
7. ADF Stationarity Test  
8. Run Main Function

The Kaggle dataset contains the following fields:

