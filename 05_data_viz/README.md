# Data Visualization

Before starting this module, work through the [Working with Data](../04_working_data) module. It covers tidy data, reshaping, cleaning, joining, and sampling. This module assumes you are comfortable loading, filtering, and summarizing a dataset with `pandas`.

To get started, open the [data visualization](data_visualization.ipynb) notebook and follow the instructions. It covers the chart types we use most in this course (bar charts, histograms, boxplots, line charts, and scatter plots) and best practices for visualization: exploring data quickly, building presentation-ready charts, and avoiding common mistakes such as overplotting. In this folder, you will also find the datasets that we will use in the examples.

## Datasets

The datasets used in this module are stored in this folder alongside the notebook, so the notebook loads them by filename (e.g., `pd.read_pickle('diamonds.pkl')`).

### GDP Data (imf_weo_data.xlsx)

This dataset contains country-level gross domestic product (GDP) data compiled by the International Monetary Fund (IMF), reported in billions of current U.S. dollars, with one column per year from 2022 to 2029. Values for later years are IMF estimates. The notebook uses it to build bar charts of the ten largest economies.

Source: International Monetary Fund, World Economic Outlook database (April 2025)

### Diamonds Data (diamonds.pkl)

The Diamonds dataset is a large, structured dataset containing detailed attributes of nearly 54,000 diamonds, including physical measurements, cut quality, color, clarity, and price.

Source: Seaborn package

### Taxi Data (taxis.pkl)

The Taxi dataset contains records of about 6,400 taxi trips in New York City in March 2019, including pickup and drop-off times, passenger counts, trip distances, fares, tips, payment type, and pickup and drop-off boroughs.

Source: Seaborn package

### Titanic Data (titanic.pkl)

The Titanic dataset contains passenger-level information from the RMS Titanic, including demographic characteristics, ticket class, fare, and survival outcomes.

Source: Seaborn package

### UA UT Seasons (ua_ut_seasons.pkl)

This dataset contains season-level performance data for the University of Alabama and the University of Tennessee football teams from 1996 to 2025. Each observation represents a single season for one school, with the value reflecting the share of games won that season.

Source: Sports Reference (College Football)
