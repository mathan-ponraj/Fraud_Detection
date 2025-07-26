# Fraud Detection Model

This project focuses on detecting fraudulent transactions using machine learning techniques. By analysing transaction patterns, the model distinguishes between genuine and fraudulent activities, helping improve security in financial systems.

---

## Project Overview

The goal is to develop a classification model that identifies fraudulent transactions within financial datasets. The workflow includes data preprocessing, feature engineering, model building, and evaluation using standard classification metrics.

---

## Features

- **Exploratory Data Analysis (EDA)**  
  Visualised transaction patterns to uncover fraud trends and data anomalies.

- **Data Preprocessing**  
  Handled missing values, encoded categorical variables, and normalised numerical features for model readiness.

- **Feature Engineering**  
  Identified significant predictors that influence fraud detection accuracy.

- **Model Building**  
  Trained classification models including Logistic Regression, Random Forest, and XGBoost for fraud classification tasks.

- **Evaluation Metrics**  
  Assessed model performance using Precision, Recall, F1-Score, and AUC-ROC to ensure reliability.

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib  
- Seaborn  
- Jupyter Notebook

---

## Project Structure
```
Fraud_Detection_Model
├── README.md # Project documentation
├── notebooks
│ └── Fraud_detection_.ipynb # Jupyter Notebook with full workflow
├── data
│ └── transactions.csv # Dataset file
├── requirements.txt # Required Python libraries

```
---

## Dataset Overview

The dataset consists of transaction records with the following features:
- **Transaction ID** — Unique identifier
- **Amount** — Transaction value
- **Time** — Time of transaction
- **Location** — Transaction location
- **Card Type** — Type of card used
- **Fraud Label (Target Variable)**  
  - `1`: Fraudulent Transaction  
  - `0`: Legitimate Transaction

---

## Results

The best-performing model achieved:
- Precision: 95%  
- Recall: 92%  
- AUC-ROC: 97%

These metrics highlight the model's strong capability to accurately identify fraudulent transactions while minimising false positives.

---

## Conclusion

This project demonstrates the application of machine learning for fraud detection by leveraging effective data preprocessing, feature engineering, and robust classification models. The framework provides a scalable approach that can be further enhanced for real-time fraud prevention systems.

---
