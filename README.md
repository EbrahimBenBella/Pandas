
# Python Pandas

**[Pandas](https://pandas.pydata.org/)** is an open-source, BSD-licensed Python library. Python package providing fast, flexible, handy, and expressive data structures tool designed to make working with 'relationa' or 'labeled' data both easy and intuitive. It aims to b|e the fundamental high-level building block for doing practical, real world complex data analysis in Python.

pandas is well suited for many different kinds of data:

* Tabular data with heterogeneously-typed columns, as in an SQL table or Excel spreadsheet
* Ordered and unordered (not necessarily fixed-frequency) time series data.
* Arbitrary matrix data with row and column labels
* Any other form of observational / statistical data sets.
# Python DataFrame

In this lesson, you will learn pandas DataFrame. It covers the basics of DataFrame, its attributes, functions, and how to use DataFrame for Data Analysis.

DataFrame is the most widely used data structure in Python pandas. You can imagine it as a table in a database or a spreadsheet.

Imagine you have an automobile showroom, and you want to analyze cars’ data to make business strategies. For example, you need to check how many vehicles you have in your showroom of type sedan, or the cars that give good mileage. For such analysis pandas DataFrame is used.
## What is DataFrame in Pandas

Dataframe is a tabular(rows, columns) representation of data. It is a two-dimensional data structure with potentially heterogeneous data.

Dataframe is a size-mutable structure that means data can be added or deleted from it, unlike data series, which does not allow operations that change its size.

## DataFrame creation

Data is available in various forms and types like CSV, SQL table, JSON, or Python structures like list, dict etc. We need to convert all such different data formats into a DataFrame so that we can use pandas libraries to analyze such data efficiently.

To create DataFrame, we can use either the DataFrame constructor or pandas built-in functions. Below are some examples.
### DataFrame constructor

```python
pandas.DataFrame(data=None, index=None, columns=None, dtype=None, copy=False)
```#### Parameters:

* **`data`**: It takes input **`dict`**, **`list`**, **`set`**, **`ndarray`**, **`iterable`**, or DataFrame. If the input is not provided, then it creates an empty DataFrame. The resultant column order follows the insertion order.


* **`index`**: (Optional) It takes the list of row index for the DataFrame. The default value is a range of integers 0, 1,…n.


* **`columns`** : (Optional) It takes the list of columns for the DataFrame. The default value is a range of integers 0, 1,…n.


* **`dtype`**: (Optional) By default, It infers the data type from the data, but this option applies any specific data type to the whole DataFrame.


* **`copy`**: (Optional) Copy data from inputs. Boolean, Default False. Only affects DataFrame or 2D array-like inputs
### Dataframe from dict

When we have data in **`dict`** or any default data structures in Python, we can convert it into DataFrame using the DataFrame constructor.

To construct a DataFrame from a **`dict`** object, we can pass it to the DataFrame constructor **`pd.DataFrame(dict)`**. It creates DataFrame using, where **`dict`** keys will be column labels, and **`dict`** values will be the columns’ data. We can also use **`DataFrame.from_dict()`** function to **[Create DataFrame from dict](**.

**Key and Imports:**

| Operator | Description |
|:----: |:---- |
| **`df`** | **pandas DataFrame object** | 
| **`s`**  | **pandas Series object** |
