# Data_Explortion_Pandas_College_Major

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

# Lego_Anaylsis
1. use HTML Markdown in Notebooks, such as section headings # and how to embed images with the <img> tag.
2. combine the groupby() and count() functions to aggregate data
3. use the .value_counts() function
4. slice DataFrames using the square bracket notation e.g., df[:-2] or df[:10]
5. use the .agg() function to run an operation on a particular column
6. rename() columns of DataFrames
7. create a line chart with two separate axes to visualise data that have different scales.
8. create a scatter plot in Matplotlib
9. work with tables in a relational database by using primary and foreign keys
10. .merge() DataFrames along a particular column
11. create a bar chart with Matplotlib

# Google Trends and Data Visualisation
1. How to use .describe() to quickly see some descriptive statistics at a glance.
2. How to use .resample() to make a time-series data comparable to another by changing the periodicity.
3. How to work with matplotlib.dates Locators to better style a timeline (e.g., an axis on a chart).
4. How to find the number of NaN values with .isna().values.sum()
5. How to change the resolution of a chart using the figure's dpi
6. How to create dashed '--' and dotted '-.' lines using linestyles
7. How to use different kinds of markers (e.g., 'o' or '^') on charts.
8. Fine-tuning the styling of Matplotlib charts by using limits, labels, linewidth and colours (both in the form of named colours and HEX codes).
9. Using .grid() to help visually identify seasonality in a time series.


# Google Play Store App Analytics
1. Pull a random sample from a DataFrame using .sample()
2. How to find duplicate entries with .duplicated() and .drop_duplicates()
3. How to convert string and object data types into numbers with .to_numeric()
4. How to use plotly to generate beautiful pie, donut, and bar charts as well as box and scatter plots

# Computation_with_NumPy_and_N_Dimensional_Arrays
1. Create arrays manually with np.array()
2. Generate arrays using  .arange(), .random(), and .linspace()
3. Analyse the shape and dimensions of a ndarray
4. Slice and subset a ndarray based on its indices
5. Do linear algebra like operations with scalars and matrix multiplication
6. Use NumPys broadcasting to make ndarray shapes compatible
7. Manipulate images in the form of ndarrays

# Seaborn_and_Linear_Regression
1. Use nested loops to remove unwanted characters from multiple columns
2. Filter Pandas DataFrames based on multiple conditions using both .loc[] and .query()
3. Create bubble charts using the Seaborn Library
4. Style Seaborn charts using the pre-built styles and by modifying Matplotlib parameters
5. Use floor division (i.e., integer division) to convert years to decades
6. Use Seaborn to superimpose a linear regressions over our data
7. Make a judgement if our regression is good or bad based on how well the model fits our data and the r-squared metric
8. Run regressions with scikit-learn and calculate the coefficients.

# Nobel_Prize_Analysis
1.How to uncover and investigate NaN values.
2. How to convert objects and string data types to numbers.
3. Creating donut and bar charts with plotly.
4. Create a rolling average to smooth out time-series data and show a trend.
5. How to use .value_counts(), .groupby(), .merge(), .sort_values() and .agg().
6. Create a Choropleth to display data on a map.
7. Create bar charts showing different segments of the data with plotly.
8. Create Sunburst charts with plotly.
9. Use Seaborn's .lmplot() and show best-fit lines across multiple categories using the row, hue, and lowess parameters.
10. Understand how a different picture emerges when looking at the same data in different ways (e.g., box plots vs a time series analysis).
11. See the distribution of our data and visualise descriptive statistics with the help of a histogram in Seaborn.
