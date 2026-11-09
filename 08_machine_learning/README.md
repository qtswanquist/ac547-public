# Machine Learning

Before starting this module, work through the [Regression](../06_regression/regression.ipynb) notebook. This module assumes you can estimate a regression (including a logistic regression) with `statsmodels` and read the summary output it produces.

To get started, open the [machine learning](ml_exercise.ipynb) notebook and follow the instructions. The notebook introduces supervised and unsupervised machine learning. It builds a confusion matrix by hand and with `scikit-learn`, evaluates classifiers with accuracy, precision, recall, and related metrics, predicts credit card defaults with logistic regression and with gradient boosting (`xgboost`), and finishes with k-means clustering on real estate sales from around campus. In this folder, you will also find the datasets that we will use in the examples.

## Datasets

The datasets used in this module are stored in this folder alongside the notebook, so the notebook loads them by filename (e.g., `pd.read_csv('spam_cm.csv')`).

### Spam Confusion Matrix (spam_cm.csv)

This dataset contains the actual and predicted spam classifications for a sample of 921 email messages, stored as two boolean columns. It supports the construction of a confusion matrix and the calculation of classification performance metrics such as accuracy, precision, and recall.

Source: Illustrative data created for this course

### Confusion Matrix Example (cm_example.xlsx)

This dataset contains observed and predicted recession classifications for each year from 1980 to 2020. The observed outcomes flag the years in which the National Bureau of Economic Research dated a recession; the predictions are illustrative.

Source: Illustrative data created for this course

### Credit Card Defaults (cc_defaults.csv)

This dataset contains demographic, financial, and repayment information for credit card clients in Taiwan, along with an indicator for whether each client defaulted on their payment in the following month.

Source: [UCI Machine Learning Repository, Default of Credit Card Clients (dataset 350)](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)

### Campus Condo Data (campus_condo_data.csv)

This dataset contains apartment, condominium, and townhouse sales from around the University of Alabama campus from November 2019 through May 2022, including the sale date, sale price, location (latitude and longitude), and basic housing characteristics such as bedrooms, bathrooms, and square footage. Observations with missing values, duplicates, outliers, and multi-unit sales were removed.

Source: Zillow (sales data, collected May–July 2022) and Google Maps (coordinates)
