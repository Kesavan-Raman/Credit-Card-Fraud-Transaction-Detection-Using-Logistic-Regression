# Credit Card Fraud Transaction Detection Using Logistic Regression

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project implements a logistic regression model to detect credit card fraud transactions. The model is trained on a dataset of credit card transactions with both fraudulent and non-fraudulent transactions, and is able to predict the likelihood of a transaction being fraudulent.

## Installation

To install the necessary libraries, run:

```bash
pip install -r requirements.txt 
```

## Dataset
The dataset used in this project is the Credit Card Fraud Detection dataset from Kaggle. This dataset contains 284,807 transactions, with 492 fraudulent transactions and 284,315 non-fraudulent transactions. The dataset is highly imbalanced, with fraudulent transactions accounting for only 0.172% of all transactions.

## Methodology
The logistic regression model was trained on the preprocessed data using scikit-learn's LogisticRegression class. The model was evaluated using metrics such as accuracy, precision, recall, and F1 score.

## Results
The logistic regression model achieved an accuracy of 0.999, precision of 0.892, recall of 0.647, and F1 score of 0.751 on the test set.
