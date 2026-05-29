# 💳 Credit Card Fraud Detection System

## 📌 Project Overview

Credit card fraud has become one of the major challenges in the financial industry due to the massive growth of online transactions. Fraudulent transactions are extremely rare compared to genuine ones, making fraud detection a highly imbalanced classification problem.

This project focuses on building a Machine Learning-based Credit Card Fraud Detection System capable of accurately identifying fraudulent transactions using advanced preprocessing, imbalance handling, model training, and explainability techniques.

The project implements and compares multiple Machine Learning algorithms including:

* Logistic Regression
* Random Forest
* XGBoost

To improve fraud detection performance on imbalanced data, SMOTE (Synthetic Minority Oversampling Technique) was applied. The project also includes SHAP Explainability for interpreting model predictions.

---

# 🚀 Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Handling imbalanced dataset using SMOTE
* Multiple Machine Learning model implementation
* Model comparison and evaluation
* ROC Curve analysis
* SHAP Explainability visualization
* Performance metric comparison

---

# 🛠️ Technologies Used

| Category                | Technologies        |
| ----------------------- | ------------------- |
| Programming Language    | Python              |
| Data Manipulation       | Pandas, NumPy       |
| Visualization           | Matplotlib, Seaborn |
| Machine Learning        | Scikit-learn        |
| Advanced ML             | XGBoost             |
| Imbalanced Learning     | SMOTE               |
| Explainability          | SHAP                |
| Development Environment | Google Colab        |

---

# 📂 Project Structure

```bash
Credit-Card-Fraud-Detection/
│
├── README.md
├── Credit_Card_Fraud_Detection.ipynb
├── requirements.txt
│
├── dataset/
│
├── images/
│   ├── roc_curve.png
│   ├── smote_distribution.png
│   ├── shap_analysis.png
│   ├── model_comparison.png
│   └── confusion_matrix.png
│
└── results/
```

---

# 🔄 Workflow

```text
Data Collection
        ↓
Data Preprocessing
        ↓
Exploratory Data Analysis
        ↓
Feature Scaling
        ↓
Train-Test Split
        ↓
SMOTE for Imbalanced Data
        ↓
Model Training
        ↓
Model Evaluation
        ↓
SHAP Explainability
```

---

# 📊 Exploratory Data Analysis

The dataset contains highly imbalanced classes where fraudulent transactions represent only a very small percentage of total transactions.

Techniques used:

* Transaction distribution analysis
* Correlation heatmaps
* Feature visualization
* Fraud vs Non-Fraud comparison

---

# ⚖️ Handling Imbalanced Data using SMOTE

Since fraudulent transactions are extremely rare, the dataset suffers from severe class imbalance.

SMOTE (Synthetic Minority Oversampling Technique) was used to generate synthetic fraud samples and balance the dataset before training.

## SMOTE Distribution

![SMOTE Distribution](images/smote_distribution.png)

---

# 🤖 Machine Learning Models Implemented

## 1️⃣ Logistic Regression

* Baseline classification model
* Fast and interpretable
* Good for comparison against advanced models

---

## 2️⃣ Random Forest

* Ensemble learning technique
* Handles complex patterns effectively
* Improves robustness and accuracy

---

## 3️⃣ XGBoost

* Advanced gradient boosting algorithm
* High performance on imbalanced classification problems
* Achieved the best fraud detection performance

---

# 📈 Model Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

---

# 📉 ROC Curve Comparison

![ROC Curve](images/roc_curve.png)

The ROC Curve comparison demonstrates the performance difference between all implemented models.

---

# 📊 Model Comparison

![Model Comparison](images/model_comparison.png)

XGBoost achieved the best overall performance in detecting fraudulent transactions.

---

# 🧠 SHAP Explainability

SHAP (SHapley Additive exPlanations) was used to interpret model predictions and understand feature importance.

## SHAP Analysis

![SHAP Analysis](images/shap_analysis.png)

This improves transparency and interpretability of the fraud detection system.

---

# 📌 Results

| Model               | Accuracy | Precision | Recall | ROC-AUC |
| ------------------- | -------- | --------- | ------ | ------- |
| Logistic Regression | XX%      | XX%       | XX%    | XX      |
| Random Forest       | XX%      | XX%       | XX%    | XX      |
| XGBoost             | XX%      | XX%       | XX%    | XX      |

> Replace the placeholder values above with your actual project results.

---

# 📚 Dataset

Dataset used:
Credit Card Fraud Detection Dataset from Kaggle

Dataset Link:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

# 🔮 Future Scope

* Real-time fraud detection system
* Deep Learning integration
* Deployment using Streamlit/Flask
* API integration for banking systems
* Hyperparameter optimization
* Advanced anomaly detection techniques

---

# ▶️ How to Run the Project

## 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
```

---

## 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Run the notebook

Open:

```bash
Credit_Card_Fraud_Detection.ipynb
```

using Jupyter Notebook or Google Colab.

---

# 👩‍💻 Author

**Sania Ayare** 

B.Tech Information Technology Student

Passionate about Machine Learning, Data Science, and AI

---

# ⭐ If you found this project useful, consider giving it a star!