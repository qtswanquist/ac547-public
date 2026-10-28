# Causal and Statistical Inference

Before starting this module, work through the [Regression](../06_regression/regression.ipynb) notebook. It covers correlation, simple and multiple regression, and logistic regression. This module assumes you can estimate a regression with `statsmodels` and read the coefficient table it produces.

To get started, open the [causal inference](causal_stat_inference.ipynb) notebook and follow the instructions. This is a conceptual, discussion-driven module rather than a coding tutorial. It asks when a correlation can be read as a causal effect (chance, confounding, experiments versus observational data, and causal models with confounders), works through two causal puzzles (a bartender suspected of skimming and a stock-price reaction to bad news), and then turns to statistical significance: what p-values and stars in a regression table do and do not mean, illustrated with coin flips, a vaccine trial, and a p-hacking simulation. Several sections link out to published charts, cartoons, and articles rather than reproducing them here, so follow those links as you go and bring your questions to class. In this folder, you will also find the datasets that we will use in the examples.

## Datasets

The datasets used in this module are stored in this folder alongside the notebook, so the notebook loads them by filename (e.g., `pd.read_pickle('under_armour_2019.pkl')`).

### Restaurant Sales (restaurant_sales.csv)

This dataset contains one row per day for a restaurant bar in calendar year 2025, with the date, day of the week, the bartender who worked that day (Sam, Alex, or Jordan), the hours the bar was open, the number of drinks made according to nightly inventory counts (bottle weights, independent of the register), and the sales rung up at the register. It is built for the Sam-the-bartender exercise, so the notebook can reveal what actually drives the pattern in sales.

Source: Simulated data created for this course

### Under Armour Data (under_armour_2019.pkl)

This dataset contains daily closing values for the S&P 500 index and Under Armour Class A stock (UAA) for the NYSE trading days from September 30 to December 6, 2019. The window surrounds November 4, 2019, the first trading day after news broke of a federal investigation into Under Armour's accounting, which coincided with the company's third-quarter results and a cut to its annual revenue forecast.

Source: Yahoo Finance

### CPU Data (cpu_data.csv)

This dataset contains information on consumer CPUs, including pricing and performance metrics, collected from PassMark in September 2022.

Source: PassMark Software
