Credit Card Fraud Transaction Detection Using Logistic Regression
This repository contains code for building a logistic regression model to detect credit card fraud transactions. The model is trained on a dataset of credit card transactions with both fraudulent and non-fraudulent transactions, and is able to predict the likelihood of a transaction being fraudulent.

Dataset
The dataset used in this project is the Credit Card Fraud Detection dataset from Kaggle. This dataset contains 284,807 transactions, with 492 fraudulent transactions and 284,315 non-fraudulent transactions. The dataset is highly imbalanced, with fraudulent transactions accounting for only 0.172% of all transactions.

Dependencies
Python 3
numpy
pandas
scikit-learn
seaborn
matplotlib
You can install the required packages using pip:

Copy code
pip install -r requirements.txt
Usage
To run the code, simply run the logistic_regression.py file:

Copy code
python logistic_regression.py
This will load the dataset, preprocess the data, train the model, and generate evaluation metrics and visualizations.

Results
The logistic regression model achieved an accuracy of 0.999, precision of 0.892, recall of 0.647, and F1 score of 0.751 on the test set. The precision-recall curve and ROC curve are shown below:

precision-recall-curve
roc-curve

License
This project is licensed under the MIT License - see the LICENSE file for details.
