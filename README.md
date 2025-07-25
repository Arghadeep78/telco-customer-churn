
# Telco Customer Churn Prediction 📞📉

This project builds an end-to-end machine learning pipeline to predict customer churn using a real-world telecom dataset. It includes data exploration, preprocessing, model tuning, and ensemble learning.

## 📌 Objective

Predict whether a customer is likely to discontinue service based on their subscription and usage data. The goal is to help telecom companies retain customers through early churn detection.

---

## 🧠 Project Highlights

- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data Cleaning and Feature Engineering
- 🔍 Feature Encoding and Scaling
- 🧪 Hyperparameter tuning with **Optuna**
- ⚖️ Class balancing with **RandomOverSampler**
- 🤖 Ensemble learning using a **Stacking Classifier**
- 📈 Evaluation with ROC-AUC, F1, Precision, Recall, Confusion Matrix

---

## 📁 Repository Structure

```
telco-customer-churn/
├── notebooks/
│   ├── 01_final_analysis.ipynb       # EDA and insights
│   └── 02_modeling_pipeline.ipynb    # Modeling and evaluation
├── requirements.txt
└── README.md
```

---

## ⚙️ Tech Stack

- Python
- Jupyter Notebook
- pandas, numpy, seaborn, matplotlib
- scikit-learn, xgboost
- imbalanced-learn, optuna, tqdm

---

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/Arghadeep78/telco-customer-churn.git
cd telco-customer-churn
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Launch the notebooks**

```bash
jupyter notebook
```

---

## 📈 Model Summary

The final model is a **Stacking Ensemble** combining:

- K-Nearest Neighbors
- Support Vector Classifier
- Random Forest
- Logistic Regression
- XGBoost

It is tuned using cross-validation and evaluated with ROC-AUC and F1 score.

---

## 📬 Contact

Created by **[Arghadeep Ghosh]**  
🔗 [LinkedIn](https://www.linkedin.com/in/arghadeep-ghosh-895b27287/)  
📫 [Email](arghadeepghosh17@gmail.com)

---

> ⭐ Star this repo if you like the project or find it helpful!
