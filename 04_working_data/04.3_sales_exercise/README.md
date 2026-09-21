# Sales Exercise

Before starting this exercise, work through the [wrangling concepts](../04.1_wrangling_concepts/wrangling_concepts.ipynb) notebook and the [diamonds exercise](../04.2_diamonds_exercise). This exercise pulls together everything in the module.

To get started, open the [sales exercise](sales_exercise.ipynb) notebook and follow the instructions. You are asked to imagine you have been assigned to a new audit client that distributes bath bombs and cowbells. Your manager hands you three related datasets covering invoices, customer orders, and shipments, and your task is to clean and join them and identify observations that require further testing. The notebook is interactive and contains incomplete code; the [solution notebook](sales_exercise_solution.ipynb) in this folder shows the finished code.

A description of the three datasets and their variables is in the [sales data sheet](sales_data_sheet.pdf) in this folder. Read it before you start wrangling.

## Datasets

The datasets used in this exercise are stored in this folder alongside the notebooks, so the notebook loads them by filename (e.g., `pd.read_csv('invoices.csv')`).

### Invoices (invoices.csv)

Invoice-level billing records from a fictitious audit client that sells consumer products. The data is in long format, with one row per invoice and product.

Source: Simulated data created for this course

### Customer Orders (customer_orders.txt)

Customer order records for the same fictitious client, one row per order, stored as a tab-delimited text file.

Source: Simulated data created for this course

### Shipping Data (shipping_data.csv)

Third-party shipment records for the same fictitious client, including shipping and delivery dates, shipping terms, and shipping weight. The customer identifier and invoice number arrive combined in a single column.

Source: Simulated data created for this course
