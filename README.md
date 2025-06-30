# Credit-Card-Fraud-Detection
This project aims to detect fraudulent credit card transactions using machine learning techniques. Using a dataset provided by Worldline and ULB, we applied and evaluated various classification algorithms Logistic Regression, Decision Trees, SVM, and Random Forest with a focus on addressing challenges like adaptive fraud strategies.

# 💳 Credit Card Fraud Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Model](https://img.shields.io/badge/Model-RandomForest-brightgreen.svg)
![Accuracy](https://img.shields.io/badge/Accuracy-99.95%25-blueviolet)

This project is focused on detecting fraudulent credit card transactions using supervised machine learning algorithms. We address the challenges of **imbalanced data**, **evolving fraud patterns**, and the **need for real-time detection** using a variety of models and evaluation metrics.

---

## 📊 Dataset

- Source: [ULB Machine Learning Group](http://mlg.ulb.ac.be)
- Contains anonymized and PCA-transformed features.
- 284,807 transactions total, with only **0.172%** fraudulent.
- Features: `V1` to `V28`, `Time`, `Amount`, `Class` (0 = genuine, 1 = fraud)

---

## 🛠️ Tools & Technologies

- **Language**: Python 3.7+
- **Libraries**:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualization
  - `scikit-learn` for modeling
- **IDE**: Jupyter Notebook, Spyder

---

## 🚀 Machine Learning Models Used

- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)
- **Random Forest** (best performing model)

---

## 📈 Evaluation Metrics

- **Accuracy**: 99.95%
- **Precision**: 98.66%
- **Recall**: 75.51%
- **F1 Score**: 85.54%
- **Matthews Correlation Coefficient**: 0.86

---

## 🔄 Flowchart

```mermaid
flowchart TD
    A[Input Raw Data] --> B[Preprocessing]
    B --> C[Train/Test Split]
    C --> D[Model Training]
    D --> E[Prediction]
    E --> F[Model Evaluation]
    F --> G[Best Model Selection]
