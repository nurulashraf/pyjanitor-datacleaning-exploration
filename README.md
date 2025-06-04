# Pyjanitor Data Cleaning Exploration

This repository contains a Google Colab notebook that demonstrates how to use **Pyjanitor**, a Python library built on top of `pandas`, to simplify and streamline data cleaning and preprocessing tasks.

## Overview

The notebook showcases the use of several powerful `pyjanitor` functions, including:

* `clean_names()` – Standardises column names to snake\_case.
* `rename_column()` – Easily rename columns.
* `fill_empty()` – Handling missing values.
* `select_columns()` – Select only the columns you need.
* Method chaining – Perform multiple operations in a single, clean line of code.

These tools help make your data wrangling workflow more readable, efficient, and pythonic.

## Contents

* `pyjanitor_datacleaning_exploration.ipynb` – The main notebook illustrating how to use Pyjanitor for real-world data cleaning.
* Example use cases for handling:

  * Missing data
  * Inconsistent column names
  * Filtering rows and selecting columns
  * Renaming for better readability

## Requirements

To run the notebook, you’ll need:

```bash
pandas
pyjanitor
```

Install using pip:

```bash
pip install pandas pyjanitor
```

## Learn More

Explore the full capabilities of Pyjanitor in its official documentation:
🔗 [https://pyjanitor-devs.github.io/pyjanitor](https://pyjanitor-devs.github.io/pyjanitor)

## License

This project is open-source and available under the [MIT License](LICENSE).
