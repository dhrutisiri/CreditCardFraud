# CreditCardFraud
This project focuses on detecting fraudulent credit card transactions using a Logistic Regression model trained on an imbalanced dataset. The original dataset contains 284,807 transactions, with only 492 labeled as fraud (Class = 1), making it a classic case for imbalanced classification.

Key Features
- Loaded and explored the dataset (creditcard.csv)
- Checked for missing values and cleaned the data
- Performed EDA (Exploratory Data Analysis) on legitimate vs. fraudulent transactions
- Used under-sampling to balance the dataset for training
- Built and trained a Logistic Regression model using scikit-learn
- Evaluated model performance using accuracy and confusion matrix

Tools & Technologies
- Python
- Pandas & NumPy
- Scikit-learn
- Google Colab

Dataset
- Source: Kaggle Credit Card Fraud Detection
- Features: V1–V28 (PCA-transformed), Amount, Time
- Target: Class (0 = Legit, 1 = Fraud)
