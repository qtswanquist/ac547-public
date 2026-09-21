# Diamonds Exercise

Before starting this exercise, work through the [wrangling concepts](../04.1_wrangling_concepts/wrangling_concepts.ipynb) notebook. This exercise assumes you are comfortable reshaping, joining, and cleaning a dataset.

To get started, open the [diamonds wrangle exercise](diamonds_wrangle_exercise.ipynb) notebook and follow the instructions. You will take the clean diamonds dataset apart — "messing it up" into two separate, awkward files — and then put it back together, practicing exports, imports, reshapes, joins, mutations, and duplicate handling along the way. The notebook is interactive and contains incomplete code; the [solution notebook](diamonds_wrangle_exercise_solution.ipynb) in this folder shows the finished code. Once you have worked through it, move on to the [sales exercise](../04.3_sales_exercise), which pulls together everything in the module. In this folder, you will also find the dataset that we will use in the exercise.

## Datasets

The dataset used in this exercise is stored in this folder alongside the notebooks, so the notebook loads it by filename (e.g., `pd.read_pickle('diamonds.pkl')`).

### Diamonds Data (diamonds.pkl)

The Diamonds dataset is a large, structured dataset containing detailed attributes of nearly 54,000 diamonds, including physical measurements, cut quality, color, clarity, and price.

Source: Seaborn package
