# 📈 Tesla Stock Prediction

## 📌 Project Overview
This project analyzes Tesla stock data and builds machine learning models to predict and classify stock movements.  
The analysis includes **EDA, feature correlation, moving averages, and two models**:  

- **Linear Regression** → Predict Closing Price (regression task)  
- **Logistic Regression** → Predict whether next day's price goes up (classification task)  

---

## 📊 Exploratory Data Analysis

- ### 1 Trend analysis of Tesla stock Closing prices over time
![Line Plot Graph](images/Tesla_Closing_Price_Over_time.png)
- ### 2 Trend analysis of Tesla stock Closing prices over the years
![Bar Plot Graph](images/trend_of_closing_price_over_the_years.png)
- ### 3 50-day vs 200-day moving averages 
![Line Plot Graph](images/Tesla_Stock_with_Moving_Average.png)
- ### 4 Correlation heatmap of stock features 
![Line Plot Graph](images/Correlation_between_Open,_High,_Low,_Volume,_and_Close.png)
- ### 5 Volume vs Closing Price scatter plot
![Line Plot Graph](images/Trading_Volume_vs_Closing_Price.png)
  

---

## 🤖 Models Used

### 🔹 Linear Regression
- Predicts the **Closing Price** of Tesla stock.  
- Evaluation metric: **R² score, RMSE, MAE**.  
- Visualization: Actual vs Predicted Closing Prices.  

### 🔹 Logistic Regression
- Predicts whether the **price will go up or down** next day (Price_Up = 1 or 0).  
- Evaluation metrics: **Accuracy, Precision, Recall, F1-score**.  
- Visualization: Confusion Matrix heatmap.  

---

## 📊 Model Comparison

### 1️⃣ Linear Regression – Actual vs Predicted Closing Price
![Linear Regression Graph](images/linear_regression.png)

### 2️⃣ Logistic Regression – Confusion Matrix
![Logistic Regression Confusion Matrix](images/logistic_regression_cm.png)

### 3️⃣ Side-by-Side Metric Comparison
![Model Performance Comparison](images/model_comparison.png)

- **Linear Regression (R²)** → measures how well regression predictions fit actual prices  
- **Logistic Regression (Accuracy)** → measures classification correctness  

---

## 🛠️ Tech Stack
- Python, Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🚀 How to Run
```bash
git clone https://github.com/YOUR-USERNAME/Tesla-Stock-Prediction.git
cd Tesla-Stock-Prediction
pip install -r requirements.txt
jupyter notebook Tesla_Stock_Prediction.ipynb

