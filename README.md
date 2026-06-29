# 📉 Stock Closing Price Prediction (PSX)

[![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Streamlit App](https://img.shields.io/badge/Framework-Streamlit-FF4B4B.svg)](https://streamlit.io/)
[![ML Models](https://img.shields.io/badge/Models-Regression%20%7C%20PCA-green.svg)](https://scikit-learn.org/)
[![Framework](https://img.shields.io/badge/Streamlit-FF4B4B.svg?style=for-the-badge&logo=Streamlit&logoColor=white)](https://streamlit.io/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Machine Learning](https://img.shields.io/badge/Scikit--Learn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)


Unlock the potential of financial forecasting! This application leverages advanced machine learning techniques to predict the closing prices of stocks listed on the **Pakistan Stock Exchange (PSX)**. By analyzing historical stock data, the model aids investors in making informed, data-driven decisions and optimizing their trading strategies.

---

## 📌 Project Overview & Objectives

Predicting stock market prices is a complex yet vital task due to the highly volatile nature of financial markets. This project focuses on forecasting the **Closing Price**—an essential indicator that reflects a stock's true value at the end of a trading session.

### 🎯 Key Goals:
* Develop a robust predictive model using historical PSX stock data.
* Provide accurate short-term forecasts to help traders minimize financial risk.
* Build an interactive, real-time web application for non-technical users to visualize stock trends.

---

## 📊 Dataset & Preprocessing Pipeline

The dataset is sourced from **Kaggle** and comprises comprehensive historical attributes of various companies listed on the Pakistan Stock Exchange.

### 🔍 Features Included:
| Feature | Description |
| :--- | :--- |
| **Date** | The specific trading day |
| **Open / High / Low** | Opening, maximum, and minimum prices of the session |
| **Close** | The target variable (Closing Price) |
| **Volume** | Total number of shares traded during the day |
| **Company Name / Sector** | Categorical identifiers for market segmentation |

### 🛠️ Data Preprocessing Techniques:
* **Data Integration:** Combined and structured raw data sheets into a unified DataFrame.
* **Exploratory Data Analysis (EDA):** Conducted deep univariate, bivariate, and multivariate analyses to understand underlying market distributions.
* **Feature Engineering:** Handled extreme market outliers, applied power transformations for normality, and generated technical lag features.
* **Dimensionality Reduction:** Utilized **Principal Component Analysis (PCA)** for optimal feature selection and removing multi-collinearity.

---

## 🤖 Model Selection & Evaluation

Multiple statistical and machine learning regression architectures were implemented and compared to find the most accurate fit:

* **Ridge Regression** (L2 Regularization)
* **Lasso Regression** (L1 Regularization)
* **Polynomial Regression** (Non-linear Mapping)

### 🏆 Best Performing Model:
> **Polynomial Regression** emerged as the most effective algorithm, capturing complex, non-linear market patterns to achieve a high **$R^2$ score of 0.8617**.

---

## ⚡ Tech Stack Used

* **Language:** Python 3.10+
* **UI/Deployment:** Streamlit, Streamlit Lottie (Animations)
* **Machine Learning:** Scikit-Learn, NumPy, Pandas
* **Dimensionality Reduction:** Principal Component Analysis (PCA)
* **Data Visualization:** Matplotlib, Seaborn

---

## 🚀 How to Run the Project Locally

Follow these steps to set up and run the application on your local machine:

### 1. Clone the Repository
```bash
git clone [https://github.com/romanahma/Stock-Closing-Price-Prediction.git](https://github.com/romanahma/Stock-Closing-Price-Prediction.git)
cd Stock-Closing-Price-Prediction