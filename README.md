# Global-Weather-Forecasting

Global Weather Forecasting and Trend Analysis

Objective

This project aims to forecast future weather trends using the **Global Weather Repository** dataset. The goal is to demonstrate both basic and advanced data science techniques — from cleaning and exploratory data analysis (EDA) to forecasting using time series models. The insights generated can help better understand global climate behaviors and environmental impacts.

> 📌 *This project is submitted as part of the PM Accelerator Assessment.*

---

 Dataset

- **Name:** Global Weather Repository
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository)
- **Description:** The dataset contains daily weather records for various cities across the globe and includes over 40 features such as temperature, humidity, wind speed, air quality, and more.

---

  Tools and Technologies

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly, Folium
- Scikit-Learn, Statsmodels, XGBoost
- Facebook Prophet / LSTM (for advanced forecasting)
- Jupyter Notebook
- Git/GitHub

---

## 🧼 1. Data Cleaning & Preprocessing

- Handled missing values via forward-fill and mean imputation.
- Detected and removed extreme outliers using IQR.
- Normalized numeric features for consistent scaling.
- Converted `lastupdated` to datetime and used it as the time index.

---

## 📊 2. Exploratory Data Analysis (EDA)

- Explored trends in temperature, precipitation, and air quality by city and continent.
- Visualized data using line plots, heatmaps, box plots, and histograms.
- Identified correlations between weather variables (e.g., temp ↔ humidity, wind ↔ AQI).

---

## 🔮 3. Time Series Forecasting

- **Basic Model:** ARIMA & Prophet for univariate forecasting
- **Advanced Models:** Compared ARIMA, Prophet, XGBoost, and LSTM
- Used metrics: MAE, RMSE, and R² Score for evaluation
- Forecasted temperature and precipitation for major cities

---

# 4. Advanced Analyses

### ✅ Anomaly Detection
- Detected outlier days with unusually high or low temperatures using statistical z-scores and Isolation Forest.

### ✅ Climate Pattern Analysis
- Explored long-term temperature changes across decades.
- Identified warming trends and regional variations.

### ✅ Environmental Impact
- Analyzed the relationship between AQI and other variables (temperature, humidity, wind speed).

### ✅ Feature Importance
- Applied XGBoost and SHAP to rank the most influential features in forecasting.

### ✅ Spatial & Geographical Patterns
- Mapped weather data using Folium to visualize air quality and temperature globally.

---

## 📌 PM Accelerator Mission

> "To empower aspiring data professionals with real-world problem-solving skills through practical projects in climate, sustainability, and environmental awareness."

This project aligns with the mission by analyzing global weather trends and forecasting climate behaviors that may inform sustainability efforts.

---

## 📈 Results & Insights

- Consistent warming trends observed in some regions (e.g., Asia, North America).
- AQI strongly influenced by wind speed and humidity.
- Prophet performed better than ARIMA in most cities with clear seasonal patterns.
- LSTM outperformed other models for multivariate long-term forecasting.

---

## 📂 Project Structure

