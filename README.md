# CreditCardFraudDetection
This project is a machine learning-based fraud detection system for credit card transactions.It leverages data preprocessing, feature engineering, and classification models to identify potentially fraudulent transactions with high accuracy.

📌 Project Overview

Credit card fraud is a major concern for financial institutions and customers.This project focuses on:

Identifying fraudulent transactions in a dataset using supervised learning.

Applying data balancing techniques to handle highly imbalanced datasets.

Evaluating different classification models based on metrics such as ROC AUC, precision, and recall.

📂 Dataset

Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

Contains 284,807 transactions with:

Time: Seconds elapsed between each transaction.

V1–V28: PCA-transformed features for confidentiality.

Amount: Transaction amount.

Class: Target variable (0 = legitimate, 1 = fraud).

Class distribution:

Legitimate: 99.83%

Fraud: 0.17%

| Model               | Precision | Recall | F1-Score | ROC AUC |
| ------------------- | --------- | ------ | -------- | ------- |
| KNN                 | 5%       | 90%    | 100%      | 97%     |
| Random Forest       | 96%       | 91%    | 8%      | 94%     |

🚀 How to Run

```
git clone https://github.com/naufaldewanto37/CreditCardFraudDetection.git
cd "REPO-NAME"
```

```
pip install -r requirements.txt
```

```
jupyter notebook creditcard.ipynb
```
