# 📚 Glossary – Module 06: Working with Data

This glossary covers key terms from working with core Python containers and Pandas for data manipulation.

---

## 🔢 Python Core Concepts
* **Dictionary:** A collection of key–value pairs.
* **List:** A mutable, ordered Python container allowing duplicates.
* **Set:** An unordered collection of unique elements.
* **Tuple:** An immutable, ordered Python container.

---

## 📦 Pandas Structures
* **DataFrame:** A two-dimensional, tabular data structure with labeled axes (rows and columns).
* **Series:** A one-dimensional labeled array capable of holding any data type.

---

## 📂 Loading and Exploring Data
* `.describe():` Summary statistics for numeric (or all) columns.
* `.head():` Shows the first 5 rows of a DataFrame.
* `.info():` Prints summary of DataFrame including dtypes and missing values.
* `read_csv():` Loads a CSV file into a DataFrame.

## 🧼 Cleaning and Fixing Data
* `.dropna()`: Drops rows or columns with missing values.
* `.fillna()`: Fills missing values with specified constant or method.
* `.isnull()` / `.notnull():` Boolean mask of missing or present data.
* `pd.to_datetime()`: Converts string/object to datetime format.
* `pd.to_numeric()`: Converts a Series to numeric type; can coerce errors to NaN.
* **Missing Value** (`NaN`): A placeholder for missing or null entries.

---

## 🧱 Column Operations
* `.apply()`: Applies a function across a Series (column) or DataFrame.
* `.drop(columns=...)`: Removes column(s) from the DataFrame.
* `.rename()`: Renames column(s) using a dictionary of {old: new}.

---

## 🔽 Sorting and Filtering
* `.query()`: Filters rows using a SQL-like syntax, e.g. `df.query("score > 90")`.
* `.sort_values()`: Sorts rows by specified column(s).
* **Boolean Masking:** Using logical operations (`&`, `|`, `~`) to filter rows.
* **Filtering:** Extracting rows based on conditional logic, e.g. `df[df["col"] > 10]`.

---

## 🧪 Wrangling Lab Concepts
* `.groupby()`: Groups rows and applies aggregation functions like `.mean()`, `.sum()`, etc.
* `.to_csv()`: Writes the DataFrame to a CSV file.
* `.value_counts()`: Shows frequency counts of unique values in a Series.
* **GroupBy:** Aggregates rows based on a shared column value.
* **Feature Engineering:** Creating new columns from existing data to enhance analysis.
