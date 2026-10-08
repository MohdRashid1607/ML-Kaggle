# Kaggle Machine Learning Projects

A collection of machine learning projects built while exploring datasets and exercises from Kaggle. Each project is developed in a Jupyter notebook and focuses on a different prediction task.

## Projects

### Credit Card Fraud Detection
Detect potentially fraudulent credit card transactions, with attention to the severe class imbalance in the dataset. The notebook uses logistic regression and includes additional classification and evaluation tools.

- [Open the notebook](credit-card-fraud-detection-system.ipynb)
- Dataset: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

### Medical Insurance Cost Prediction
Predict individual medical insurance charges from a dataset containing 1,338 records and 7 columns. The notebook compares a linear regression baseline with tree-based regression models.

- [Open the notebook](exercise-1-medical-insurance-cost-prediction.ipynb)
- Dataset file expected by the notebook: `insurance.csv`

### Online Gaming Behavior Classification
Predict whether a player wins or loses from online gaming behavior data. The notebook compares logistic regression and random forest classification approaches.

- [Open the notebook](exercise-2-online-gaming-behavior-classification.ipynb)
- Dataset file expected by the notebook: `online_gaming_behavior_dataset.csv` (40,035 records, 13 columns)

## Repository Contents

```text
ML-Kaggle/
|-- README.md
|-- credit-card-fraud-detection-system.ipynb
|-- exercise-1-medical-insurance-cost-prediction.ipynb
`-- exercise-2-online-gaming-behavior-classification.ipynb
```

Datasets are not included in this repository. Add the required CSV files locally or configure the notebook paths for your Kaggle environment before running the notebooks.
