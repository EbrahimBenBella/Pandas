
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

**Key and Imports:**

| Operator | Description |
|:----: |:---- |
| **`df`** | **pandas DataFrame object** | 
| **`s`**  | **pandas Series object** |
