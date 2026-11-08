# Credit Card Fraud Detection Using Machine Learning

## Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning classification algorithms.

The goal is to identify potentially fraudulent transactions while minimizing false alarms. The project compares Logistic Regression and Random Forest models using multiple evaluation metrics.

## Objectives

- Analyze credit card transaction data.
- Identify fraudulent transaction patterns.
- Build machine learning classification models.
- Compare model performance.
- Evaluate fraud detection using precision, recall, F1-score, ROC-AUC and PR-AUC.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

The project uses the Credit Card Fraud Detection dataset available on Kaggle.

Dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset contains legitimate and fraudulent credit card transactions.

## Machine Learning Algorithms

Two classification algorithms were implemented:

1. Logistic Regression
2. Random Forest Classifier

## Model Evaluation

Both models were evaluated using precision, recall, F1-score, ROC-AUC, PR-AUC and confusion matrices.

### Performance Comparison

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Precision | 0.056 | 0.971 |
| Recall | 0.874 | 0.705 |
| F1-score | 0.106 | 0.814 |
| ROC-AUC | 0.966 | 0.925 |
| PR-AUC | 0.672 | 0.796 |

### Confusion Matrix Results

**Logistic Regression**
- True Negatives: 55,262
- False Positives: 1,389
- False Negatives: 12
- True Positives: 83

**Random Forest**
- True Negatives: 56,649
- False Positives: 2
- False Negatives: 28
- True Positives: 67

## Key Findings

- Logistic Regression detected more fraudulent transactions, identifying 83 out of 95 fraud cases.
- Random Forest achieved higher precision and produced only 2 false positive predictions.
- Random Forest achieved a higher F1-score and PR-AUC.
- Logistic Regression achieved a higher ROC-AUC and recall.

## Conclusion

This project demonstrates how Machine Learning can be applied to credit card fraud detection.

Logistic Regression was more effective at identifying fraudulent transactions at the selected classification threshold, while Random Forest was more effective at reducing false alarms.

The comparison highlights the importance of selecting a model based on the practical requirements of fraud detection systems.

Further improvements could include threshold optimization, hyperparameter tuning and additional model evaluation.

## Author

**Mohammed Afnan Saad**

GitHub: https://github.com/afnan12saad
