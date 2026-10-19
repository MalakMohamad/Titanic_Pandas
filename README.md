# Titanic Dataset: Data Cleaning with Pandas

A beginner data-analysis project using Python and Pandas to inspect and prepare the Titanic dataset for further exploration.

## Objective

Practise loading a dataset, reviewing its structure, handling missing values, and creating useful features for analysis.

## Workflow

1. Load the Titanic dataset into a Jupyter Notebook.
2. Inspect columns, data types, and summary statistics with methods such as `info()` and `describe()`.
3. Handle missing values, including filling missing `Age` values with the column mean.
4. Drop `Cabin`, which has a high proportion of missing values in the dataset used.
5. Fill missing values in `Embarked`.
6. Create `FamilySize` and `IsAlone` features to support further analysis.

## Tools

- Python
- Pandas
- Jupyter Notebook

## Dataset

The project uses the Titanic dataset associated with the Kaggle Titanic competition: [Kaggle dataset page](https://www.kaggle.com/c/titanic/data).

## Current Scope

This repository focuses on data loading, basic exploration, data cleaning, and feature engineering. Visualization and deeper analysis can be added as future improvements.

## Skills Practised

- Reading and inspecting tabular data
- Summarizing columns and data types
- Treating missing values
- Selecting and removing columns
- Creating features from existing data

## Run Locally

1. Clone the repository.
2. Install the required packages:
   ```bash
   pip install pandas jupyter
   ```
3. Open the notebook in Jupyter and run the cells.

Note: imputation and column-removal decisions depend on the analytical goal. They are learning choices for this project, not universal rules for every dataset.
