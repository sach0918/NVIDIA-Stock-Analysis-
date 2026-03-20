# NVIDIA-Stock-Analysis

## 📌 Project Overview

This project analyzes NVIDIA’s stock performance from 1999 to 2026 and builds a machine learning model to predict next-day stock price movement. The analysis focuses on identifying trends across different technological eras and understanding the relationship between financial indicators and stock valuation.

---

## 🎯 Objectives

* Analyze long-term stock price trends of NVIDIA
* Study the impact of different growth eras (GPU, AI, Data Center)
* Explore relationships between revenue, market cap, and stock price
* Use technical indicators (SMA, RSI) for trend analysis
* Build a model to predict next-day stock movement

---

## 📊 Dataset Description

* Time Period: 1999–2026
* Features:

  * Stock Prices (Open, Close, High, Low)
  * Trading Volume
  * Market Capitalization
  * Quarterly Revenue
  * Technical Indicators (SMA 20, 50, 200, RSI)
  * Era classification
  * Stock split information

---

## 🔍 Exploratory Data Analysis

The following analyses were performed:

* Stock price trends over time and across different eras
* Trading volume patterns, especially during the Generative AI era
* Market capitalization growth across different phases
* Relationship between revenue and market cap
* Correlation analysis between financial indicators
* Stock split distribution across eras

---

## 📈 Technical Analysis

* Moving Averages (SMA 20, 50, 200) used to identify trends
* RSI used to detect momentum and overbought/oversold conditions
* Volume analysis to understand market participation

---

## 🤖 Machine Learning Model

* Model: Random Forest Classifier
* Objective: Predict whether stock price will increase the next day
* Target Variable:

  * 1 → Price goes up
  * 0 → Price goes down or stays same

### Features Used:

* SMA 20, SMA 50, SMA 200
* RSI (14-day)
* Volume

---

## 📊 Model Performance

* Accuracy: **58%**

### Key Observations:

* High recall for upward movements (~96%)
* Poor performance in detecting downward movements
* Model shows bias toward predicting upward trends

---

## 📌 Feature Importance

* Volume is the most important predictor
* Moving averages (trend indicators) strongly influence predictions
* RSI has relatively lower importance

---

## 🔑 Key Insights

* NVIDIA’s valuation increased significantly during the AI and data center growth phases
* Trading volume plays a crucial role in stock price movement
* Moving averages effectively capture long-term trends
* The model is biased due to class imbalance (more upward movements)
* Revenue and market cap show strong positive correlation

---

## ⚠️ Limitations

* Model struggles to predict downward movements
* High correlation among moving averages (feature redundancy)
* Stock market data is noisy and difficult to predict
* Accuracy alone is not sufficient to evaluate performance

---

## 🚀 Future Improvements

* Apply time-series models (LSTM, ARIMA)
* Improve class balance using resampling techniques
* Add macroeconomic indicators
* Optimize model using hyperparameter tuning

---

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 📌 Conclusion

This project demonstrates how financial data, technical indicators, and machine learning can be combined to analyze stock behavior and make predictions. While the model shows moderate predictive capability, it highlights the complexity and uncertainty inherent in financial markets.

---

