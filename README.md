# Decision Trees & Random Forest: Loan Repayment Prediction
## ARTI 308: Machine Learning - Assignment

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-444876?style=for-the-badge&logo=seaborn&logoColor=white)

### Assignment Overview
This repository contains a comparative machine learning Assignment that predicts whether a borrower will pay back their loan in full. The Assignment uses publicly available data from LendingClub.com and compares the performance of a single **Decision Tree** against an ensemble **Random Forest** classifier.

### Workflow & Tasks Completed
1. **Exploratory Data Analysis (EDA):** Visualized the distribution of FICO scores and loan purposes using `seaborn` and `matplotlib`.
2. **Feature Engineering:** Handled categorical variables by converting them into dummy variables using `pd.get_dummies()`.
3. **Model Training (Decision Tree):** Trained a single decision tree and evaluated its baseline performance.
4. **Model Training (Random Forest):** Trained a Random Forest classifier consisting of 600 individual trees to reduce variance and improve predictive accuracy.
5. **Evaluation & Comparison:** Generated Classification Reports and Confusion Matrices for both models. Evaluated the trade-off between overall accuracy and minority class recall due to the imbalanced nature of the dataset.

### Files in this Repository
* `Lab9.ipynb`: The Jupyter Notebook containing the full code, EDA, and model evaluations.
* `loan_data.csv`: The dataset used for training the models.
