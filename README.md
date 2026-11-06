# Credit Score Classification

Classifies customers into credit score tiers (Poor, Standard, Good) from account details, debts and repayment behaviour.

## Dataset
- Files: `train.csv` (100,000 rows, 28 columns) and `test.csv` (50,000 rows, 27 columns, no target)
- Target: `Credit_Score` (Poor / Standard / Good)

## Approach
1. Data cleaning: replaced corrupted text placeholders, parsed text fields (such as credit history age) into numbers, imputed missing values with medians
2. EDA with Plotly and Seaborn
3. Models compared on accuracy and macro F1; XGBoost performed best
4. Hyperparameter tuning of XGBoost and predictions on the test file

## Results
- Tuned XGBoost accuracy: 71.4% on the validation set (3 classes, 20,000 validation rows)

## Tech stack
Python, Pandas, NumPy, Scikit-Learn, XGBoost, Plotly, Matplotlib, Seaborn

## Author
Swati Tiwari | [GitHub](https://github.com/tiwariswati186-alt) | [LinkedIn](https://www.linkedin.com/in/swati-tiwari-37972317a)
