# 📉 Telecom Customer Churn Prediction (81% Accuracy)

## 📌 Project Overview
Customer Churn is one of the most critical metrics for telecom companies. This project aims to build a high-performance classification model to predict which customers are likely to cancel their service. By identifying these customers early, the business can deploy targeted retention strategies to minimize revenue loss.

## 🚀 Key Achievements
* **Top Performing Model:** **AdaBoost Classifier** achieved the highest accuracy of **81%**.
* **Benchmarking:** Evaluated **6 different algorithms**, including XGBoost, Random Forest, and Logistic Regression.
* **Optimization:** Used `GridSearchCV` to fine-tune hyperparameters, significantly improving the model's ability to generalize on unseen data.

## 🛠️ Tech Stack
* **Python:** Data manipulation and modeling.
* **Scikit-learn:** Implementation of AdaBoost and evaluation metrics.
* **Pandas & Numpy:** Data cleaning and feature transformation.
* **Matplotlib & Seaborn:** Exploratory Data Analysis (EDA) and results visualization.

## 📁 Analysis Workflow

### 1. Exploratory Data Analysis (EDA)
* Identified key churn drivers such as **Contract Type**, **Monthly Charges**, and **Tenure**.
* Visualized the impact of "Month-to-month" contracts on the high churn rate.

### 2. Preprocessing & Feature Engineering
* **Encoding:** Transformed categorical variables using One-Hot Encoding.
* **Scaling:** Normalized numerical features to improve model convergence.
* **Feature Importance:** Analyzed which variables contribute most to the prediction.

### 3. Model Evaluation
Instead of just looking at accuracy, the model was evaluated using:
* **Confusion Matrix:** To track True Positives (Churners correctly identified).
* **ROC-AUC Curve:** To measure the trade-off between sensitivity and specificity.



## 💡 Results & Insights
* **The Winner:** **AdaBoost** proved to be the most robust, effectively handling the complexities of the telecom dataset.
* **Business Recommendation:** The company should focus on customers with "Month-to-month" contracts and high monthly charges, as the model identified them as the highest risk group.

