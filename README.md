# 🛒 Retail Sales Prediction using Machine Learning

This project aims to predict retail product sales based on historical warehouse and sales data using machine learning models. Accurate sales forecasting enables better inventory management, demand planning, and supply chain optimization.

## 📁 Project Structure

- `Retail sales prediction using machine learning.ipynb`: Jupyter notebook containing data analysis, model training, and evaluation steps.
- `retail_warehouse_data.csv`: Dataset used for training and testing the models.

## 📊 Problem Statement

The goal is to build a regression model that can predict the number of units sold for various retail products based on:
- Product features
- Warehouse location
- Pricing details
- Historical sales trends

## 🧠 Machine Learning Techniques Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Feature scaling, encoding, and data cleaning
- Evaluation metrics: Mean Squared Error (MSE), Root Mean Squared Error (RMSE), R² score

## 📌 Key Features

- Exploratory Data Analysis (EDA)
- Data preprocessing pipeline
- Model training and comparison
- Visualization of prediction results

## 📂 Dataset Overview

The dataset includes columns like:
- `Product_ID`
- `Warehouse_Location`
- `Price`
- `Units_Sold`
- `Date`
- `Category`

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sourav-003/retail-sales-prediction.git
   cd retail-sales-prediction
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook
   ```

4. Open and run:
   ```
   Retail sales prediction using machine learning.ipynb
   ```

## 📈 Result

The best-performing model demonstrated strong predictive capability on unseen data and helped identify key features driving sales performance.

## 🧪 Future Improvements

- Hyperparameter tuning (GridSearchCV)
- Time series-based models (e.g., ARIMA, Prophet)
- Incorporate real-time or seasonal data

## 📄 License

This project is for educational purposes only. Use it at your discretion for learning or prototyping.

---
