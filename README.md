# College Major using pandas

1. Use .head(), .tail(), .shape and .columns to explore your DataFrame and find out the number of rows and columns as well as the column names.
2. Look for NaN (not a number) values with .findna() and consider using .dropna() to clean up your DataFrame.
3. You can access entire columns of a DataFrame using the square bracket notation: df['column name'] or df[['column name 1', 'column name 2', 'column name 3']]
4. You can access individual cells in a DataFrame by chaining square brackets df['column name'][index] or using df['column name'].loc[index]
5. The largest and smallest values, as well as their positions, can be found with methods like .max(), .min(), .idxmax() and .idxmin()
6. You can sort the DataFrame with .sort_values() and add new columns with .insert()
7. To create an Excel Style Pivot Table by grouping entries that belong to a particular category use the .groupby() method

 
# Programming_Languages_using_matplotlib

1. used .groupby() to explore the number of posts and entries per programming language
2. converted strings to Datetime objects with to_datetime() for easier plotting
3. reshaped our DataFrame by converting categories to columns using .pivot()
4. used .count() and isna().values.any() to look for NaN values in our DataFrame, which we then replaced using .fillna()
5. created (multiple) line charts using .plot() with a for-loop
6. styled our charts by changing the size, the labels, and the upper and lower bounds of our axis.
7. added a legend to tell apart which line is which by colour
8. smoothed out our time-series observations with .rolling().mean() and plotted them to better identify trends over time.
