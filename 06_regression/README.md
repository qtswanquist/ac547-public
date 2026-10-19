# Regression

Before starting this module, work through the [Data Visualization](../05_data_viz/data_visualization.ipynb) notebook. It covers the chart types we use most in this course and best practices for building and reading plots. This module assumes you are comfortable loading, summarizing, and plotting a dataset with `pandas` and `seaborn`.

To get started, open the [regression](regression.ipynb) notebook and follow the instructions. It covers correlation, simple linear regression, multiple regression, and logistic regression for binary outcomes. In this folder, you will also find the datasets that we will use in the exercises.

## Datasets

The datasets used in this module are stored in this folder alongside the notebook, so the notebook loads them by filename (e.g., `pd.read_pickle('diamonds.pkl')`).

### Sim Data (sim_data.csv)

This dataset consists of multiple simulated datasets containing two correlated variables, x and y, with 100 observations per dataset.

Source: Simulated data created for this course

### Diamonds Data (diamonds.pkl)

The Diamonds dataset is a large, structured dataset containing detailed attributes of nearly 54,000 diamonds, including physical measurements, cut quality, color, clarity, and price.

Source: Seaborn package

### Anscombe's Quartet (anscombe.pkl)

Anscombe's Quartet is a classic illustrative dataset consisting of four small datasets with identical or nearly identical statistical patterns. Despite these similarities, each dataset exhibits a distinct underlying data pattern when visualized.

Source: Seaborn package

### CPU Data (cpu_data.csv)

This dataset contains information on consumer CPUs, including pricing and performance metrics, collected from PassMark in September 2022.

Source: PassMark Software

### Market Data (market_data.pkl)

This dataset contains daily closing values for the S&P 500 index, Tesla stock (TSLA), Walmart stock (WMT), and the SPDR Gold Shares ETF (GLD) for all 250 NYSE trading days of calendar year 2025. 

Source: Yahoo Finance

### Logit Data (logit_data.csv)

This dataset consists of simulated observations designed to illustrate binary outcome modeling using logistic regression. Each observation includes a continuous predictor variable and a binary outcome indicating whether an event occurred.

Source: Simulated data created for this course
