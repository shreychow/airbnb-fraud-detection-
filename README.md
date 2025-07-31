# Airbnb NYC Fraud Detection 

This project uses the Airbnb NYC listings dataset to detect potentially fraudulent or suspicious listings.


## Goal
Predict whether an Airbnb listing is suspicious based on:
- Price anomalies (e.g., less than $30)
- Zero reviews with high availability
- Missing host information

## Models Used
- Logistic Regression
- Random Forest
- GridSearchCV for optimization

## Results
- Accuracy: 99%
- F1 Score (suspicious class): ~0.29 (class imbalance)

## Files
- `DefineAndSolveMLProblem.ipynb`: Jupyter notebook with full analysis
- `airbnbListingsData.csv`: Raw dataset (if included)

##  How to Run
1. Run the notebook

## Notes
- The dataset is highly imbalanced. Model performance on the suspicious class may be limited.
- Further improvements could involve oversampling or anomaly detection techniques.
