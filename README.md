# 🎬 MovieIQ – Movie Success Prediction Dashboard

An interactive **machine learning dashboard** that predicts whether a movie will be successful based on financial and audience features such as budget, popularity, runtime, and ratings.


## 📌 Project Overview

MovieIQ is an end-to-end data science project that combines:

* 📊 Exploratory Data Analysis (EDA)
* 🧪 Statistical hypothesis testing
* 🤖 Machine Learning modeling
* 🌐 Interactive dashboard deployment

The goal is to classify whether a movie is **successful (profitable)** or not using real-world movie data.

---

## 🧠 Problem Statement

Can we predict if a movie will be profitable based on its:

* Budget
* Popularity
* Runtime
* Average vote rating

A movie is considered **successful** if:

> **Revenue > Budget**

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit** – Web app framework
* **Pandas & NumPy** – Data processing
* **Seaborn & Matplotlib** – Visualization
* **Scikit-learn** – Machine Learning
* **SciPy** – Statistical testing

---

## 📂 Features

### 🔍 Interactive Data Exploration

* Filter movies by genre and rating
* View dataset previews and summary statistics

### 📊 Visual Analytics

* Budget vs Revenue scatter plot
* Success-based feature comparisons
* Confusion matrix visualization

### 🧪 Statistical Analysis

* T-test (vote average vs success)
* Chi-square test (genre vs success)

### 🤖 Machine Learning Model

* Random Forest Classifier
* Handles class imbalance
* Performance evaluation using:

  * Accuracy
  * Precision, Recall, F1-score

### 🎯 Prediction System

* User input form for:

  * Budget
  * Popularity
  * Runtime
  * Vote Average
* Outputs:

  * Success/Failure prediction
  * Confidence score

### ⬇️ Data Export

* Download filtered dataset as CSV

---

## 📊 Model Details

* **Algorithm:** Random Forest Classifier
* **Target Variable:** Success (1 = profitable, 0 = not profitable)
* **Train-Test Split:** 70/30
* **Evaluation Metrics:**

  * Accuracy
  * Classification Report
  * Confusion Matrix





---

## 📈 Future Improvements

* Add feature importance visualization
* Implement advanced models (XGBoost, Logistic Regression)
* Perform hyperparameter tuning
* Use cross-validation for better evaluation
* Improve genre handling (multi-label encoding)
* Deploy with a custom domain

---

