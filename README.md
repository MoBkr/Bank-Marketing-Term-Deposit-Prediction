# 🏦 Bank Marketing Term Deposit Prediction

This is a **machine learning classification project** based on a real-world marketing dataset from a Portuguese banking institution. The goal is to predict whether a client will subscribe to a **term deposit** after being contacted by a marketing campaign.


---

## 📌 Table of Contents

- [Overview](#overview)
- [Dataset Information](#dataset-information)
- [EDA and Preprocessing](#eda-and-preprocessing)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## 🧠 Overview

This project involves building a predictive model to help a bank determine which customers are most likely to subscribe to a term deposit based on demographic and campaign-related attributes.

We perform:
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Feature encoding
- Model training (Logistic Regression, Decision Tree, Random Forest, SVM)
- Model evaluation using multiple metrics

---

## 📂 Dataset Information

The dataset contains the following important columns:

### 🎯 Target Column:
- `y`: Whether the client subscribed to a term deposit (`yes`=1, `no`=0)

### 👤 Customer Info:
- `age`, `marital`, `education`, `job`
- `housing`, `loan`, `contact`
- `day`, `month`, `duration`
- `campaign`, `previous`, `pdays`
- `preferred`: Contact channel (e.g., telephone, cellular)

---

## 📊 EDA and Preprocessing

- Visualized class distribution and feature patterns
- Checked for missing or unknown values
- Encoded categorical features using **Label Encoding** and **One-Hot Encoding**
- Scaled numerical features using **StandardScaler**

---

## 🤖 Modeling

Trained and compared several models:
- ✅ Logistic Regression
- 🌳 Decision Tree Classifier
- 🌲 Random Forest Classifier
- 💠 Support Vector Machine (SVM)

Used **train/test split** for evaluation.

---

## 📈 Evaluation

Used the following metrics to evaluate performance:
- **Accuracy**
- **F1-Score**
- **Confusion Matrix**
- **Classification Report**

You can find detailed metric outputs and visualizations in the notebook.

---

## 🧰 Technologies Used

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn (for visualization)
- Scikit-learn (for modeling and evaluation)
- Jupyter Notebook

---

## 💻 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bank-marketing-prediction.git
   cd bank-marketing-prediction
