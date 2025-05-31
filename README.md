# DATS 2103: Data Mining – Final Project  
📍 The George Washington University | Fall 2024  
👩🏽‍💻 Created by Aba Pobee

This repository contains the final project for DATS 2103: Data Mining, where I applied core predictive analytics concepts using Python to a real-world dataset. The project explores historical wage trends in the U.S. private sector and predicts future earnings using regression modeling, blending technical rigor with economic storytelling.

---

## 📊 Project Overview

### 🔍 Predicting Private-Sector Wages: A Regression Analysis

Using 50 years of data (1974–2024) from the U.S. Bureau of Labor Statistics, I examined how average hourly earnings for production and nonsupervisory private-sector employees evolved over time. I then built and compared regression models to predict earnings based on historical trends and economic indicators like unemployment rates.

### 🧠 Skills Demonstrated
- Data retrieval from federal sources (BLS)
- Data wrangling and merging with `pandas`
- Exploratory data analysis and feature engineering
- Regression modeling: Linear, Lasso, and Principal Component Regression
- Model evaluation using MSE and R²
- Forecasting and limitations assessment

---

## 🗃️ Repository Contents

- `final_report.pdf` – Project summary and visualizations (≤ 2,000 words)
- `final_project.ipynb` – IPython notebook for data cleaning, modeling, and evaluation
- `employment_data.csv` – Raw dataset compiled from BLS on wages and unemployment (1974–2024)

---

## 🧪 Project Highlights

- 📈 **Historical Patterns**: Visualized wage growth by decade and identified significant increases in the 2014–2024 window, likely driven by the COVID-19 pandemic and economic shifts.
- 📉 **Economic Indicators**: Used monthly unemployment rate and its rate of change as predictors to better understand labor market pressures on wage dynamics.
- 🤖 **Model Comparison**:
  - **Linear Regression**: Best-performing model with R² ≈ 0.97 and low MSE.
  - **Lasso Regression**: Slightly less accurate but highlighted key predictors for interpretability.
  - **Principal Component Regression**: Useful for dimensionality reduction but did not outperform simpler models.
- 📉 **Forecasting Challenge**: Predicted earnings for Dec 2024 using the linear model (~$26/hr) revealed limitations due to economic volatility and missing real-time data.

---

## 🔍 Key Insights

- Lagged wages and unemployment rates are strong predictors of wage movement.
- Economic shocks like the 2008 recession and 2020 pandemic are clearly reflected in employment trends.
- Regression models work well on historical data, but predictive accuracy drops when applied to uncertain future scenarios.

---

## 🛠️ Technologies & Libraries Used

- Python 3, Jupyter Notebook  
- `pandas`, `numpy`, `matplotlib`, `seaborn`  
- `sklearn` for regression models and evaluation  
- U.S. Bureau of Labor Statistics datasets

---

## 📫 Let’s Connect

If you're working in data science, labor economics, or predictive analytics, I'd love to connect!  
📍 [LinkedIn](https://linkedin.com/in/abapobee)
