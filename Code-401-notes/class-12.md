# Class 12 - Pandas

## Reading

## Pandas in 10
[Source Credit](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)
- import pandas as pd
- Each column in a DataFrame is a Series
- 
- Creating a Series by passing a list of values, letting pandas create a default integer index:
    - `s = pd.Series([1, 3, 5, np.nan, 6, 8])`  
- Creating a DataFrame by passing a NumPy array, with a datetime index using date_range() and labeled columns:
    - `pd.date_range("20130101", periods=6)`
- The columns of the resulting DataFrame have different dtypes:
- Use DataFrame.head() and DataFrame.tail() to view the top and bottom rows of the frame
-  fundamental difference between pandas and NumPy: NumPy arrays have one dtype for the entire array, while pandas DataFrames have one dtype per column.
- Selecting single column `df["A"]` equivalent to df.A
- Selecting via [](__getitem__) which slices the rows `df[0:3]`
- Lots of other options for selections...


### Additional Resources
[Pandas - Getting Started](https://pandas.pydata.org/pandas-docs/stable/getting_started/intro_tutorials/index.html)

[Real Python - Pandas Tutorials](https://realpython.com/learning-paths/pandas-data-science/)

## Videos

### What is Pandas
[Source Credit](https://www.youtube.com/watch?v=dcqPhpY7tWk&t=391s)
-  load, prepare, manipulate, analyze data
- data visualization
- statistical investigation of data by manipulating the data shown

## Bookmark and review
[Master Pandas](https://towardsdatascience.com/be-a-more-efficient-data-scientist-today-master-pandas-with-this-guide-ea362d27386)

## Things I want to know more about
- Pandas, Math, BigO (still)