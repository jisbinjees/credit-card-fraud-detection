# Credit card fraud detection



## Project Overview
The integrity of financial transactions is an incredibly important issue facing financial institutions and credit card companies alike. Having the ability to classify the legitimacy of a transaction to protect clients not only gives customers peace of mind, but is expensive. This dataset contains credit card transactions made by European cardholders in the year 2023. 

## Project Goals
Can we use historical transaction data to predict whether a transaction is fraudulent or legitimate?

## Data Overview
Our dataset from Kaggle has comprises over 550,000 records, and the data has been anonymized to protect the cardholders' identities. The primary objective of this dataset is to facilitate the development of fraud detection algorithms and models to identify potentially fraudulent transactions.

## Key Features 
id: Unique identifier for each transaction
V1-V28: Anonymized features representing various transaction attributes (e.g., time, location, etc.)
Amount: The transaction amount
Class: Binary label indicating whether the transaction is fraudulent (1) or not (0)

## Model Results

For a financial institution dealing with identifying fraud, Sensitivity and F1 - Score might be more important metrics. F1- Score reprsents a more balanced result as it is the harmonic mean between Precision and Recall. Sensitivity is more important in the sense that we are more interested in identifying fraud than than identifying legitimate customers.

- Sensitivity/Recall for Logistic Regression Model 1 : 0.58
- F1 Score for Logistic Regression Model 1 : 0.68

## Dataset
https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023