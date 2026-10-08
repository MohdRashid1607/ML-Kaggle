# 🚀 Kaggle Machine Learning Projects

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit%20Learn-yellow?style=for-the-badge&logo=scikit-learn)

Welcome to the **Kaggle Machine Learning Projects** repository! This collection features various machine learning projects built while exploring datasets and solving real-world challenges on Kaggle. Each project is developed and documented in a dedicated Jupyter Notebook, focusing on different predictive modeling tasks including classification and regression.

## 📁 Repository Structure

```text
ML-Kaggle/
├── README.md
├── credit-card-fraud-detection-system/
│   └── credit-card-fraud-detection-system.ipynb
├── medical-insurance-cost-prediction/
│   └── exercise-1-medical-insurance-cost-prediction.ipynb
└── online-gaming-behavior-classification/
    └── exercise-2-online-gaming-behavior-classification.ipynb
```

## 🛠 Projects Overview

### 1. 💳 Credit Card Fraud Detection
Detect potentially fraudulent credit card transactions, addressing the challenge of severe class imbalance in the dataset. 
- **Techniques Used**: Logistic Regression, Class Imbalance Handling, Classification Metrics
- **Location**: `credit-card-fraud-detection-system/credit-card-fraud-detection-system.ipynb`
- **Dataset**: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

### 2. 🏥 Medical Insurance Cost Prediction
Predict individual medical insurance charges based on personal attributes from a dataset containing 1,338 records and 7 columns.
- **Techniques Used**: Linear Regression (Baseline), Tree-based Regression Models
- **Location**: `medical-insurance-cost-prediction/exercise-1-medical-insurance-cost-prediction.ipynb`
- **Dataset File**: Expected as `insurance.csv` 

### 3. 🎮 Online Gaming Behavior Classification
Predict whether a player will win or lose based on their online gaming behavior and engagement metrics. 
- **Techniques Used**: Logistic Regression, Random Forest Classification
- **Location**: `online-gaming-behavior-classification/exercise-2-online-gaming-behavior-classification.ipynb`
- **Dataset File**: Expected as `online_gaming_behavior_dataset.csv` (40,035 records, 13 columns)

## ⚙️ Setup & Installation

To run these notebooks locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ML-Kaggle.git
   cd ML-Kaggle
   ```

2. **Install dependencies**:
   Make sure you have standard machine learning libraries installed. You can install them via pip:
   ```bash
   pip install jupyter pandas numpy scikit-learn matplotlib seaborn
   ```

3. **Download Datasets**:
   Datasets are **not** included in this repository. Please download the corresponding CSV files from Kaggle or your data source and place them in the correct project subdirectories before running the notebooks.

4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request if you have suggestions for improvement.
