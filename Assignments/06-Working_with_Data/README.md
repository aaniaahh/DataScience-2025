# 🧰 Module 06 – Working with Data

This module introduces core Python and Pandas tools for manipulating, cleaning, and inspecting datasets. It's the messy middle of any data science project—and now you're equipped to handle it like a pro.

---

## 🎯 Learning Objectives
By the end of this module, you should be able to:

Describe and use Python’s built-in containers (`list`, `dict`, `tuple`, `set`)
Load tabular data from `.csv` using Pandas
Explore, index, and select data using `.loc[]`, `.iloc[]`, and masks
Handle missing values and perform basic data cleaning
Add, remove, and modify columns in a DataFrame
Filter and sort data using multiple strategies
Prepare a dataset for visualization or modeling

---

## 📕 Glossary

[Foundations_Glossary.md](https://github.com/rugbyprof/3603-Programming-for-Data-Science/blob/main/Assignments/06-Working_with_Data/glossary.md) – Key terms and definitions for quick reference.

---

## 📚 Notebooks
1. [01-lists_dicts_and_tuples.ipynb](https://github.com/aaniaahh/DataScience-2025/blob/main/Completed/06-Working_with_Data/01_lists_dicts_and_tuples.ipynb)	
2. [02-pandas_series_and_dataframes.ipynb](https://github.com/aaniaahh/DataScience-2025/blob/main/Completed/06-Working_with_Data/02_pandas_series_and_dataframes.ipynb)	
3. [03-loading_and_exploring_data.ipynb](https://github.com/aaniaahh/DataScience-2025/blob/main/Completed/06-Working_with_Data/03_loading_and_exploring_data.ipynb)	
4. [04-indexing_and_selection.ipynb](https://github.com/aaniaahh/DataScience-2025/blob/main/Completed/06-Working_with_Data/04_indexing_and_selection.ipynb)	
5. [05-basic_cleaning.ipynb]()	
6. [06-column_operations.ipynb]()	
7. [07-sorting_and_filtering.ipynb]()
8. [08-pandas_wrangle_lab.ipynb]

---

## 📦 Module Recap
Data doesn’t come clean and labeled like a science fair project. This module guided you through the messy, glorious reality of data wrangling in Python using native tools and Pandas.

By now, you should feel confident:
* Recognizing Python's core data containers (`list`, `tuple`, `dict`, `set`)
* Working with `Pandas Series` and `DataFrames`
* Loading CSVs, exploring structure, and identifying issues
* Cleaning, transforming, and filtering datasets
* Writing your cleaned data back out for analysis or sharing

---

## 🎯 Key Takeaways
* Missing values are common and must be handled early to avoid broken logic later.
* Data types matter: just because it looks like a number doesn’t mean Python agrees.
* Column operations let you build new insights and features from existing ones.
* Filtering and sorting are the core tools of exploratory data analysis (EDA).
* Pandas is powerful, but you are the one asking the questions and defining the structure.

---

## 🗂️ Suggested Datasets
* Titanic Dataset (`seaborn.load_dataset("titanic")`)
* Pokémon Stats (`data/pokemon.csv`)
* UFO Sightings (`data/ufo.csv`)
* Iris Dataset (`seaborn.load_dataset("iris")`)
* Students (`data/students.csv` or `data/students.json`)

--- 

## 🛠️ Tips
* Try chaining methods (`df[df.col > 5].sort_values("col2")`) but don’t be afraid to split steps for clarity.
* Use `.copy()` when slicing to avoid `SettingWithCopyWarning`.
* Use `%timeit` to compare loops vs. vectorized filters.