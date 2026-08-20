# Nobel Prize Dataset Analysis

Exploratory data analysis of Nobel Prize laureates from **1901 to 2023**.

## Objective

This project explores demographic and historical patterns among Nobel Prize laureates. It focuses on gender, countries of birth, the share of U.S.-born winners, female representation across decades and categories, and repeated names in the dataset.

## Dataset

The dataset contains **1,000 records** and **18 variables**, including:

- year and prize category,
- laureate name and type,
- gender,
- birth date, city and country,
- organisation details,
- death date, city and country.

## Questions explored

- Which gender appears most often among laureates?
- Which birth country appears most frequently?
- How has the proportion of U.S.-born laureates changed by decade?
- In which decade and category was female representation highest?
- Who was the first female Nobel Prize laureate?
- Which names occur more than once in the dataset?

## Selected findings

- **Male** is the most common recorded gender among laureates.
- The **United States of America** is the most common birth country in the dataset, with **291** laureates.
- The highest share of female laureates by decade and category occurs in **Literature in the 2020s**.

## Analysis workflow

1. Load and inspect the dataset.
2. Analyse gender distribution.
3. Identify the most common birth countries.
4. Calculate the proportion of U.S.-born laureates by decade.
5. Compare female representation across decades and Nobel Prize categories.
6. Identify the first female laureate and repeated names.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repository structure

```text
nobel-prize-dataset/
├── data/
│   └── nobel.csv
├── images/
    └── Nobel_Prize.png
├── notebooks/
    └── notebook.ipynb
```

## How to run

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

Open the notebook from the `nobel-prize-dataset` directory so that the relative path to the dataset works correctly:

```text
nobel-prize-dataset/nootbooks/notebook.ipynb
```
