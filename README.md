# Store-Sales-Analysis-Python
In this project i used Python Pandas &amp; Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

### I started by cleaning the data. Tasks during this section included:

    1) Dropping NaN values from the DataFrame
    2) Removing rows based on a condition
    3) Changing the type of columns (to_numeric, to_datetime, astype)
    4) Once I cleaned up the data a bit, I moved to the data exploration section. 

### In this section, I explored 5 high-level business questions related to the data:

    1) What was the best month for sales? How much was earned that month?
    2) What city sold the most products?
    3) What time should advertisements be displayed to maximize the likelihood of customer purchases?
    4) What products are most often sold together?
    5) What product sold the most? Why do I think it sold the most?

### To answer these questions, I walked through many different pandas and matplotlib methods. They included:
    1) Concatenating multiple CSVs together to create a new DataFrame (pd.concat)
    2) Adding columns
    3) Parsing cells as strings to make new columns (.str)
    4) Using the .apply() method
    5) Using groupby to perform aggregate analysis
    6) Plotting bar charts and line graphs to visualize the results
    7) Labeling the graphs
