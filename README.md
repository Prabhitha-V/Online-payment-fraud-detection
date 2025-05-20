# 🛡️ Online Payment Fraud Detection

This project builds a robust fraud detection system using advanced machine learning techniques to classify online transactions as fraudulent or legitimate. Leveraging a large-scale dataset of 1 million records, the model combines interpretability and performance by integrating decision trees and boosting algorithms, with a strong focus on real-time fraud detection.

---

## 🎯 Objectives

- Detect fraudulent online transactions using data-driven classification models.
- Analyze transaction patterns through exploratory data analysis (EDA).
- Apply and compare ensemble methods (AdaBoost, Gradient Boosting) for improved accuracy.
- Develop a user-interactive fraud prediction system using Decision Trees.

---

## 📊 Dataset Overview

- **Source**: [Kaggle – Online Payment Fraud Detection](https://www.kaggle.com/datasets)
- **Size**: 1 million transactions
- **Features**:
  - Transaction type, amount, sender/receiver balances
  - Target variable: `isFraud` (binary)

---

## ⚙️ Tools & Technologies

- **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **Plotly**
- **Scikit-learn**: DecisionTree, AdaBoost, GradientBoosting
- **Jupyter Notebook**, **Google Colab**

---

## 🧠 Key Components

- 📈 **EDA**: Used distplots, boxplots, correlation heatmaps, and univariate analysis to identify trends and outliers.
- 🌳 **Decision Tree Classifier**: Powers a user-interactive prediction system with transparent logic.
- 🚀 **AdaBoost & Gradient Boosting**:
  - Boost model accuracy on imbalanced data
  - Achieved strong performance in F1 and precision-recall metrics

---

## 📈 Results

- Ensemble methods significantly improved fraud classification accuracy.
- Feature importance revealed strong predictive value in transaction type and balance deltas.
- Demonstrated interpretable fraud prediction with decision paths via Decision Tree.


---

## 🧪 Future Scope

- Apply undersampling/oversampling to handle class imbalance more effectively.
- Fine-tune ensemble hyperparameters with GridSearchCV.
- Deploy real-time fraud detection via a web or API interface.

---

## 🧾 Summary

This project demonstrates a scalable and intelligent approach to online fraud detection by combining interpretability, statistical rigor, and machine learning strength. It highlights the importance of ensemble learning and interactive prediction in modern cybersecurity solutions.

