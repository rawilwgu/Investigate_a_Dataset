# Investigate_a_Dataset

Investigating a Dataset throughout the data wrangling process.

**Requirements:**

numpy
pandas
matplotlib.pyplot
seaborn

## Functions Defined

**scatter_chart(arg1, arg2)**
Takes in two arguments, each representing the columns that you want to plot within a scatter plot.
    Parameters:
    N (int): Random number to help with randomized colors.
    colors (np.random.rand(N)): Sets different colors randomly to each plot point.
    df (pd.DataFrame): The pandas DataFrame containing the data.
    arg1, arg2 (str): The columns used to create the scatterplot.
    title (str): The title of the scatterplot.
    xlabel (str): The label for the x-axis.
    ylabel (str): The label for the y-axis.
    Returns: None

**histogram_chart(arg1, x, y)**
Takes in three arguments. arg1 is the column to plot the frequency on. x and y are the labels.
    Parameters:
    df (pd.DataFrame): The pandas DataFrame containing the data.
    arg1, arg2 (str): The columns used to create the plot.
    title (str): The title of the plot.
    xlabel (str): The label for the x-axis.
    ylabel (str): The label for the y-axis. 
    Returns: None

## Goal of Assignment
The goal tackles into two questions:
    1. How does the budget for the movies compare to the revenue earned in 2010? Or when adjusted for inflation?
    2. Which movies have the highest popularity and revenue?

In the Data Wrangling stage, we are viewing the rows and understanding the data further.
In the Data Cleaning stage, we address the columns with missing values.
In the Exploratory stage, we create our plots to attempt to answer the questions defined.



