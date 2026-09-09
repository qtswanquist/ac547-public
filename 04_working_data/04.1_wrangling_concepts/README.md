# Wrangling Concepts

To get started, open the [wrangling concepts](wrangling_concepts.ipynb) notebook and follow the instructions. It covers tidy data, common data forms, number and date formats, duplicates, missing values, replacing values and conditionals, combining data vertically and horizontally, and sampling. Once you have worked through it, move on to the [diamonds exercise](../04.2_diamonds_exercise) and the [sales exercise](../04.3_sales_exercise), which put these ideas to work. In this folder, you will also find the datasets that we will use in the examples.

## Datasets

The datasets used in this module are stored in this folder alongside the notebook, so the notebook loads them by filename (e.g., `pd.read_csv('invoice_data.csv')`).

### Invoice Data (invoice_data.csv)

A small invoice dataset used to demonstrate wrangling tasks on data you can read at a glance. It contains an invoice number, an invoice date and time, an amount, a customer name, a shipping point indicator, and a quantity. It deliberately includes a duplicated invoice, inconsistent spacing in the customer names, and dates stored as text.

Source: Illustrative data created for this course

### Shipping Data (shipping_data.csv)

A companion shipping dataset in long format, with one row per invoice and attribute. Each invoice has a shipping number, a shipping date and time, a receiving date and time, and a weight. It is used to demonstrate reshaping long data to wide, parsing inconsistent date formats, handling a missing value, and joining to the invoice data.

Source: Illustrative data created for this course
