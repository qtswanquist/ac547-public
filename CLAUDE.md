# CLAUDE.md - Course Project Instructions

## About this file

This file tells AI coding assistants how to write code for this course, so the code they suggest already follows the conventions below.

- **Claude Code** reads this file automatically. It applies to work anywhere in the repository, including module folders like `02_python_basics` — keep the whole course folder open in VS Code rather than a single module folder and it will always be in effect.
- **GitHub Copilot** reads the same rules from `.github/copilot-instructions.md`, which is a copy of this file.

You are welcome to read it and to add rules of your own — learning to steer an AI assistant is part of this course. If you edit one copy, the other will not change with it, so change both if you want the two tools to behave the same way.

## Project Overview

This is the AC547 Data Analytics for Accounting course repository at the University of Alabama. Work involves data science tasks using Python in VS Code.

Python runs from the course virtual environment in `.venv`. Notebooks must have the `.venv` kernel selected before running.

## Code Style

- Follow PEP 8 for all Python code.
- Use 4-space indentation (never tabs).
- Use snake_case for variables and functions, PascalCase for classes.
- Keep lines under 79 characters where practical.
- Use f-strings for string formatting.
- Use descriptive variable names (e.g., `revenue_df` not `df1`).

## Library Preferences

- **DataFrames**: Always use `pandas`. Do not use polars or other alternatives.
- **Visualization**: Prefer `seaborn` over matplotlib for plots. Use matplotlib only for low-level customization that seaborn cannot handle.
- **Statistics**: Use `statsmodels` for regression and statistical modeling.
- **Machine Learning**: Use `scikit-learn` for ML tasks. Use `xgboost` when gradient boosting is needed.
- **Numerical computation**: Use `numpy` for array operations.

## Import Conventions

```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import statsmodels.formula.api as smf
```

## Data Science Conventions

- Load data into pandas DataFrames; use `.head()`, `.info()`, and `.describe()` for initial exploration.
- Use method chaining where it improves readability (e.g., `.groupby().agg().reset_index()`).
- Where a notebook sets a seaborn theme, use `sns.set_theme(style="whitegrid")` for consistency.
- Always add a title to plots. Label axes as well, unless the automatic labels seaborn takes from the column names already describe them completely (e.g., generic `x` and `y`).
- Use `random_state=42` (or similar) for reproducibility in randomized algorithms.
- Print model summaries and key metrics (R-squared, RMSE, accuracy) after fitting.

## File and Project Structure

- Jupyter notebooks (`.ipynb`) are the primary working format.
- Course modules are organized by numbered directories (e.g., `01_getting_started`, `02_python_basics`).
- Each module folder holds the datasets its notebooks need. Notebooks load them by filename with no directory prefix, e.g. `pd.read_pickle('diamonds.pkl')`.
- Check the actual filename in the module folder before writing a load call; do not guess.
- Prefer `pd.read_pickle()` for datasets available as `.pkl`; use `pd.read_csv()` / `pd.read_excel()` for the others.

## Dependencies

All packages for this course are pinned in `requirements.txt` and installed into the `.venv`. Use only the packages listed there. If a task appears to need a package that is not listed, explain why instead of installing one.
