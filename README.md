# Financial Fraud Detection using Machine Learning

## Case Study

### Problem
Financial institutions face massive losses due to fraudulent transactions. The challenge is detecting **rare fraud events** accurately within **millions of highly imbalanced transactions** while minimizing false positives.

### Context
This project analyzes **6.3M+ real-world financial transactions** and builds a scalable **fraud detection system** using classical machine learning and imbalance-handling techniques.

### Impact
- Achieved **99.6% accuracy** with an optimized Random Forest model
- **98% recall** on fraud cases (critical for fraud prevention)
- Near-perfect **ROC-AUC: 0.999**
- Successfully detected fraudulent transactions in unseen data

### Why It Matters
High recall and precision are essential in fraud detection to **prevent financial loss** while maintaining customer trust and minimizing false alerts.

---

## What I Did

- Designed an **end-to-end fraud detection pipeline** on large-scale data
- Cleaned and preprocessed **6M+ transactions**
- Handled **extreme class imbalance** using SMOTE
- Engineered fraud-relevant behavioral features
- Trained, evaluated, and optimized multiple ML models
- Built a real-time fraud prediction workflow

---

## How I Did It (STAR Method)

### Situation
The dataset was extremely large, noisy, and **highly imbalanced** (<0.2% fraud cases), making naive modeling ineffective.

### Task
Build a scalable, high-recall fraud detection model while minimizing false positives.

### Action
- Performed data cleaning (null checks, duplicate removal)
- Encoded categorical variables (transaction types)
- Detected and removed extreme outliers using **Z-score**
- Analyzed feature correlations to reduce redundancy
- Applied **SMOTE** to balance minority fraud class
- Standardized numerical features using **StandardScaler**
- Trained and compared:
  - Logistic Regression (baseline)
  - Random Forest Classifier
- Evaluated models using:
  - Accuracy, Precision, Recall, F1-score
  - ROC-AUC and Precision-Recall AUC
- Tuned Random Forest using **RandomizedSearchCV**
- Built a prediction system for new transactions

### Result
- **Optimized Random Forest Performance**
  - Accuracy: **99.6%**
  - Precision: **97.6%**
  - Recall: **98.1%**
  - F1-score: **97.8%**
  - ROC-AUC: **0.999**
- Strong generalization on unseen data
- Reliable detection of fraudulent transactions

---

## Tech Stack

- **Programming Language:** Python
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Models:** Logistic Regression, Random Forest
- **Imbalance Handling:** SMOTE (imbalanced-learn)
- **Scaling:** StandardScaler
- **Hyperparameter Tuning:** RandomizedSearchCV
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1, ROC-AUC, PR-AUC

---

## Key Results / Business Impact

- Detected fraud with **high recall**, reducing financial loss
- Minimized false positives while maintaining strong accuracy
- Demonstrated scalable ML pipeline for real-world financial systems
- Built a strong baseline for production-grade fraud detection

---

## Example Prediction

```text
Input Transaction:
- Type: TRANSFER
- Amount: 181.00
- Balance Change: Sudden drop to zero

Model Output:
Fraudulent
```
