# AI-ML-internship-task-2
This project predicts the next day’s stock closing price using historical data from Yahoo Finance. Features like Open, High, Low, and Volume are used to train a Linear Regression or Random Forest model. The results are visualized by comparing actual vs predicted closing prices.
Here’s a structured summary for your stock price prediction project:

---

### ✅ **○ Task Objective**

To predict the **next day’s closing stock price** using historical market data with features such as *Open*, *High*, *Low*, and *Volume*.

---

### 📂 **○ Dataset Used**

* **Source**: Yahoo Finance via the `yfinance` Python library
* **Stock**: Apple Inc. (`AAPL`)
* **Time Period**: January 2020 to December 2023
* **Features Used**: Open, High, Low, Volume
* **Target Variable**: Next day’s Close price

---

### 🤖 **○ Models Applied**

* **Linear Regression**
* (Optional alternative: **Random Forest Regressor**)

---

### 📊 **○ Key Results and Findings**

* The model was trained using historical price features to predict the next day’s closing price.
* **Evaluation metrics** like Mean Squared Error and R² Score were used to assess accuracy.
* The plotted **Actual vs Predicted Closing Prices** show the model captures general price trends but may not predict exact values due to market volatility.
* **Linear Regression** is simple and interpretable, while **Random Forest** may provide better performance with non-linear patterns.


