# 🕵️ Crime Data Analysis & Forecasting (2020–Present)

This project analyzes real-world crime data from 2020 to the present, sourced from the LA Open Data portal. It includes data cleaning, exploratory data analysis, geospatial and demographic insights, and crime forecasting using time series models.

---

## 📌 Project Goals
- Clean and preprocess a raw crime dataset (~800K+ records)
- Visualize overall trends, seasonality, and patterns
- Identify high-frequency crime types and regions
- Analyze correlations with demographics
- Forecast future crimes using ARIMA models

---

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels (ARIMA)
- Jupyter Notebook

---

## 📊 Key Insights
- Crimes increased steadily from 2020 to 2023, with a drop in 2024 (possibly due to policy/data issues)
- **July to September** are peak months for crime
- **Friday** has the highest crime rates across the week
- Top 5 crimes include Battery, Burglary, and Theft
- Chi-square tests show strong correlation between gender and crime type
- ARIMA models predict ~430 crimes/day in the short-term forecast

---

## 🔮 Forecasting
We used an **ARIMA(1,0,1)** model to predict daily crime frequencies for a 10-day horizon. This allows law enforcement agencies to anticipate trends and allocate resources accordingly.

---

## 🧪 Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/anaghavs09/crime-data-analysis.git
cd crime-data-analysis-and-forecasting
