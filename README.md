# Pandas DataFrame Operations
This repository contains notes and examples on various DataFrame operations in Pandas, focusing on financial data analysis.

## Creating DataFrames
Various ways to create DataFrames including from dictionaries, 2D lists, and lists of dictionaries.

## Setting Index
Use `.set_index(column_name)` to set a column as the index of the DataFrame.

## Column Indexing
Access columns using `df['column_name']`. For multiple columns, use a list: `df[['col1', 'col2']]`.

## Row Indexing
Use `.loc['index_name']` or `.iloc[row_number]` for row indexing. For multiple rows, use lists.

## Accessing Specific Values
Methods to access specific values in a DataFrame.

## Selecting Ranges
Use `.loc[[row_names], [column_names]]` or `.iloc[[row_numbers], [column_numbers]]` to select ranges.

## Conditional Filtering
Filter DataFrame based on conditions.

## Adding Columns
Methods to add new columns to a DataFrame.

## Adding Rows
Techniques for adding new rows to a DataFrame.

## Deleting Columns/Rows
Use `drop()` with `axis=1` for columns, `axis=0` for rows.

## Changing Column Labels
Use `df.columns`, `df.index.name`, or `df.rename()` to change column labels.

## Changing Data Types
Use `.astype()` to change data types of columns.

## String Operations on Columns
Perform string operations on DataFrame columns using `.str` accessor.

## Querying Data
Use `query()` method for filtering data based on complex conditions.

## Filtering with regex
Use `filter()` with `items` or `regex` for advanced filtering.

## Sorting and Ranking
Use `.sort_values()` for sorting and `.rank()` for ranking.

## Index Operations
Perform set operations on indexes: `.union()`, `.intersection()`, `.difference()`.

## Grouping Data
Use `.groupby()`, `.get_group()`, and `.agg()` for grouping and aggregating data.

## Concatenating DataFrames
Use `pd.concat()` to concatenate DataFrames.

## Appending DataFrames
Use `.append()` to append DataFrames.

## Merging DataFrames
Use `.merge()` to merge DataFrames based on column values.

## Joining DataFrames
Use `.join()` to join DataFrames based on index.

## Slicing
Various slicing techniques for DataFrames.

## MultiIndex Columns
Create MultiIndex columns using `pd.MultiIndex.from_product()`.

## Stack and Unstack
Use `.stack()` and `.unstack()` for reshaping DataFrames.

## Pivot Tables
Create pivot tables using `pd.pivot()`.

## Melting DataFrames
Use `.melt()` to reshape DataFrames from wide to long format.
