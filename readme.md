# Loan Default Risk Modeling

**Carson Pratt**
UC Berkeley — B.A. Data Science & Economics

This project is built using the [Loan Default](https://www.kaggle.com/datasets/yasserh/loan-default-dataset) dataset from Kaggle, and published as a Jupyter notebook.

To access the Jupyter notebook, open the ipynb file.

Libraries Used: pandas, NumPy, scikit-learn, statsmodels, matplotlib

### Overview

Built a weighted logistic regression model to predict borrower loan default risk using financial and loan-level characteristics. The project focuses on identifying high-risk borrowers and evaluating classification tradeoffs in an imbalanced dataset.

### Approach

* Cleaned and imputed financial features (credit score, LTV, DTI, interest rate)  
* Removed extreme outliers  
* Stratified train-test split  
* Implemented logistic regression with class weighting  
* Evaluated using confusion matrix, precision, recall, and F1-score  

### Results

Recall: 0.59  
Precision: 0.28  
Accuracy: 0.53  



