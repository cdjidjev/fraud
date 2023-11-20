
# Fraudulent Transaction Prediction

This project aims to predict fraudulent financial transactions using machine learning techniques.

## Data

The data comes from a [Kaggle dataset](https://www.kaggle.com/datasets/vardhansiramdasu/fraudulent-transactions-prediction) of simulated debit card transactions containing 6362620 rows and 11 features. The target variable is a binary column `isFraud` indicating fraudulent transactions.

## Notebook Overview

The Jupyter notebook provides an analysis and modeling workflow including:

- Data exploration and visualization 
- Preprocessing to clean the data and engineer features
- Training various classification models including Logistic Regression, Random Forest, etc.
- Comparing model performance to select the best approach
- Analyzing feature importance of the top model

## Key Findings

- The dataset is highly imbalanced with only a small fraction of transactions being fraudulent
- Correlated features like account balances are identified for removal
- Logistic Regression and Random Forest have the best performance, with ~99% accuracy
- Random Forest feature importance highlights informative transaction properties

## Usage

To replicate this analysis:

1. Clone this repo
2. Download the transactions dataset from [Kaggle](https://www.kaggle.com/datasets/vardhansiramdasu/fraudulent-transactions-prediction)
3. Run the Jupyter notebook

Let me know if any sections need additional detail or if you would like me to expand the documentation.
