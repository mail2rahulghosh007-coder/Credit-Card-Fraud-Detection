# Credit-Card-Fraud-Detection
This project implements a machine learning–based approach to detect fraudulent credit card transactions.  
Due to the highly imbalanced nature of fraud data I apply Undersampling.

The complete workflow — from data loading to model evaluation — is implemented in a Jupyter Notebook.

- **Dataset Name:** Credit Card Fraud Dataset  
- **Transactions:** 284,807  
- **Fraudulent Transactions:** 492  
- **Features:** 30  
  - `V1`–`V28`: 
  - `Time`: Time elapsed between transactions  
  - `Amount`: Transaction amount  
- **Target Variable:** `Class`  
  - `0` → Legitimate  
  - `1` → Fraud  

 The dataset file `creditcard.csv` is stored using **Git LFS** due to its large size.

The project follows these steps:

1. Data loading and inspection  
2. Exploratory Data Analysis (EDA)  
3. Feature scaling  
4. Handling class imbalance  
5. Model training  
6. Performance evaluation( Train accuracy is 94.5% and test accuracy is 93.9%)

