# Class_Imbalance_Tutorial
A practical tutorial on handling class imbalance in classification tasks using logistic regression. This project explores the impact of techniques like class weighting and SMOTE (Synthetic Minority Oversampling Technique) on model performance, using a real-world credit card fraud detection dataset.

## What You'll Learn

- Why accuracy is misleading on imbalanced datasets
- How to evaluate models using:
  - Precision, Recall, F1-score
  - Confusion Matrix
  - Precision-Recall (PR) Curves and AUC
- How to apply and compare:
  - Baseline Logistic Regression
  - Class-Weighted Logistic Regression
  - SMOTE Oversampling + Logistic Regression
 
## Contents
- `ML_Tutorial.ipynb` – Jupyter Notebook with code, visuals, and explanation
- `LICENSE` – MIT License

## Dataset Source

This project uses the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), published by the ULB Machine Learning Group. It contains anonymised transactions made by European cardholders over two days in 2013.

> ⚠️ **Note:** The `creditcard.csv` file is too large to be included directly in this GitHub repository (exceeds 25 MB limit).  
> To run the notebook, please download the dataset from the [Kaggle link above](https://www.kaggle.com/mlg-ulb/creditcardfraud) and place the file in the **same directory** as the notebook.
