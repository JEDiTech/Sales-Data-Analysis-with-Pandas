# Sales-Data-Analysis-with-Pandas
In this exercise, I analyzed a company's sales data using Python Pandas &amp; Matplotlib in Jupyter Notebook,guided by a video tutorial by @KeithGalli on YouTube, in order to answer pertinent business questions.

The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

We started by cleaning our data. 
Tasks during this section included:

- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Once we have cleaned up our data a bit, we moved to the data exploration section. 
In this section we explored 5 high level business questions related to our data:

- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What product sold the most? Why do you think it sold the most?
- What products are most often sold together?

To answer these questions we walk through many different pandas & matplotlib methods. They include:

Concatenating multiple .csv files together to create a new DataFrame (pd.concat)
Adding columns
Parsing cells as strings to make new columns (.str)
Using the .apply() method
Using groupby to perform aggregate analysis
Plotting bar charts and lines graphs to visualize our results
Labeling our graphs, etc.
