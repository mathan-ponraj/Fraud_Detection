# Fraud Detection Model

This project focuses on detecting fraudulent transactions using machine learning techniques. By analysing transaction patterns, the model classifies transactions as legitimate or fraudulent, helping improve security in financial systems.

---

## Project Overview

The objective is to build a classification model that accurately identifies fraudulent transactions based on historical data. The workflow includes data preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation using key classification metrics.

---

## Features

- **Exploratory Data Analysis (EDA)**  
  Analysed transaction patterns to uncover trends and detect data anomalies.

- **Data Preprocessing**  
  Handled missing values, outlier detection using Z-Score, encoding categorical variables, and scaling numerical features.

- **Feature Engineering**  
  Selected and engineered significant features to improve model accuracy.

- **Model Building & Tuning**  
  Trained classification models including Random Forest and Logistic Regression. Performed hyperparameter tuning using GridSearchCV and RandomizedSearchCV for optimal performance.

- **Evaluation Metrics**  
  Evaluated model using Accuracy, Precision, Recall, F1-Score, and AUC-ROC.

---

## Libraries Used

- **NumPy** – Numerical computations and array operations
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualisation
- **Seaborn** – Statistical visualisations and correlation plots
- **SciPy (zscore)** – Outlier detection
- **Scikit-learn (sklearn):**
  - Data Splitting: `train_test_split`
  - Scaling: `StandardScaler`
  - Models: `RandomForestClassifier`, `LogisticRegression`
  - Hyperparameter Tuning: `GridSearchCV`, `RandomizedSearchCV`
  - Metrics: `accuracy_score`, `precision_score`, `recall_score`, `f1_score`, `classification_report`

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


---

## Dataset Overview

The dataset contains transaction records with the following features:
- **Transaction ID** — Unique identifier for each transaction
- **Amount** — Transaction value
- **Time** — Timestamp of transaction
- **Location** — Transaction location
- **Card Type** — Type of card used for the transaction
- **Fraud Label (Target Variable)**  
  - `1` — Fraudulent Transaction  
  - `0` — Legitimate Transaction

---

## Results

The best-performing model achieved the following metrics:
- Precision: 95%  
- Recall: 92%  
- AUC-ROC: 97%

These results demonstrate the model's effectiveness in accurately identifying fraudulent transactions while minimising false positives.

---

## Conclusion

This project demonstrates the use of machine learning models for fraud detection in financial transactions. By applying robust data preprocessing, feature selection, and model tuning techniques, the model achieves high precision and recall, making it a reliable tool for detecting fraudulent activities in large datasets.

---
