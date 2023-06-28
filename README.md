# Pandas_datascience_library

pandas is a software library written for the Python programming language for data manipulation and analysis.

Pandas is a Python library used for working with data sets.

It has functions for analyzing, cleaning, exploring, and manipulating data.

The name "Pandas" has a reference to both "Panel Data", and "Python Data Analysis" and was created by Wes McKinney in 2008.

Pandas allows us to analyze big data and make conclusions based on statistical theories.

Pandas can clean messy data sets, and make them readable and relevant.

Relevant data is very important in data science.

Pandas gives you answers about the data. Like:

Is there a correlation between two or more columns?

What is average value?

Max value?

Min value?

Pandas are also able to delete rows that are not relevant, or contains wrong values, like empty or NULL values. This is called cleaning the data.

### Pandas Series

Pandas series is a one-dimensional data structure. It can hold data of many types including objects, floats, strings and integers. You can create a series by calling pandas.Series().

An list, numpy array, dict can be turned into a pandas series. You should use the simplest data structure that meets your needs. In this article we’ll discuss the series data structure.

Create series

Introduction

Pandas comes with many data structures for processing data. One of them is a series.
The syntax for a series is:

import pandas as pd

s = pd.Series()

print(s)

This creates an empty series.

Create series from list

To turn a list into a series, all you have to do is:

>>> import pandas as pd
>>> 
>>> items = [1,2,3,4]
>>> 
>>> s = pd.Series(items)
>>> 
The contents of s is:

0 1
1 2
2 3
3 4
dtype: int64

By default is assigns an index. First it shows the index, then the element value.

### Pandas Dataframe

A Pandas DataFrame is a 2 dimensional data structure, like a 2 dimensional array, or a table with rows and columns.

ExampleGet your own Python Server

Create a simple Pandas DataFrame:

import pandas as pd

data = {
  "calories": [420, 380, 390],
  "duration": [50, 40, 45]
}

#load data into a DataFrame object:

df = pd.DataFrame(data)

print(df) 


