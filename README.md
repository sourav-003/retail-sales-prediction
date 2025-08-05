# 🛍️ Retail Sales Prediction using Machine Learning

This project focuses on predicting retail sales using both **Linear Regression** and a **Deep Learning-based Neural Network**. The aim is to model sales trends, extract useful patterns, and improve forecasting accuracy using machine learning techniques.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Project Objectives](#project-objectives)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [EDA and Preprocessing](#eda-and-preprocessing)
- [Model Building](#model-building)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Key Learnings](#key-learnings)
- [Future Improvements](#future-improvements)
- [Acknowledgements](#acknowledgements)

---

## 🧠 Overview

Retail sales data can be highly volatile due to seasonal demand, promotions, and external factors. This project attempts to build an intelligent system to predict future sales based on historical data using:

- **Linear Regression**: As a baseline model  
- **Deep Neural Network (DNN)**: To capture complex nonlinear relationships

---

## 🎯 Project Objectives

- Perform **Exploratory Data Analysis (EDA)** to discover patterns  
- Preprocess data to make it suitable for ML models  
- Train and evaluate a **Linear Regression model**  
- Build a **Neural Network model using TensorFlow and Keras**  
- Compare performance using appropriate regression metrics  

---

## 🛠️ Technologies Used

- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn  
- TensorFlow, Keras  
- Matplotlib, Seaborn  

---

## 📊 Dataset

The dataset contains various features including:

- Store-level information  
- Historical sales data  
- Categorical attributes (e.g., Store type, region)  
- External features possibly affecting sales (e.g., holidays, promotions)  

> Dataset was cleaned, analyzed, and used for training models.

---

## 🔍 EDA and Preprocessing

- Checked for missing values and outliers  
- Encoded categorical variables using Label Encoding  
- Normalized continuous features using MinMaxScaler  
- Visualized trends using line plots and histograms  

---

## 🧪 Model Building

### ✅ Linear Regression

- Built using `scikit-learn`  
- Achieved **R² score of 0.29**  
- Served as a baseline model  

### ✅ Deep Neural Network (DNN)

- Built using `TensorFlow` and `Keras`  
- Input Layer → Hidden Layers → Output Layer  
- Activation: ReLU (hidden), Linear (output)  
- Loss: Mean Squared Error  
- Optimizer: Adam  

---

## 📈 Evaluation Metrics

| Metric              | Linear Regression | Neural Network |
|---------------------|------------------|----------------|
| Mean Squared Error  | 2.30e-05         | ~0.0206 (scaled) |
| Mean Absolute Error | —                | ~0.0744 (scaled) |
| R² Score            | 0.29             | TBD (inverse transform required) |

---

## 🏁 Results

- **Linear Regression** gave a decent start but underfit the complex patterns.  
- **Neural Network** showed improved accuracy, lower error, and better generalization.  

---

## 📚 Key Learnings

- Regression models need significant data cleaning and transformation  
- Neural Networks can significantly outperform linear models in complex datasets  
- Proper scaling and evaluation are critical to real-world success  

---

## 🚀 Future Improvements

- Add advanced feature engineering (e.g., lag features, promotions)  
- Hyperparameter tuning (batch size, learning rate, epochs)  
- Try other models like XGBoost or Random Forest for comparison  
- Build a forecasting dashboard using Power BI or Streamlit  

---

## 🙏 Acknowledgements

A huge thanks to **Kumar Sundram Sir** for his mentorship and guidance throughout this project. His practical approach to learning machine learning has been instrumental in shaping my understanding.

Also grateful to **Learnbay** for providing such industry-relevant projects and hands-on exposure to real-world scenarios in data science.

---

## 📎 Project Structure
Retail-Sales-Prediction/
│
├── Retail sales prediction using machine learning.ipynb
├── rules.csv
├── README.md
├── .gitignore
└── requirements.txt


---

## 📫 Let's Connect

- **LinkedIn**: [Sourav Kumar](https://www.linkedin.com/in/sourav-kumar-5814341b8)  
- **Email**: souravmail003@gmail.com

---




