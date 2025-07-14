# Exploratory Data Analysis with Pandas and Matplotlib

This Readme file will provide a comprehensive guide for performing exploratory data analysis on three different datasets `ufo`, `u.user`, and `movies` using the Pandas library and data visualization using Matplotlib.

## Data Loading
The first step of the data analysis process involves loading the data into a Pandas DataFrame. The datasets `ufo`, `u.user`, and `movies` will be loaded into their respective DataFrames named `ufo`, `user`, and `movie`.

## Data Exploration
The next step of the process will be exploring the data. We will perform the following tasks:

- Print the head and the tail of the DataFrames
- Examine the default index, data types, and shape of the DataFrames
- Count the number of missing values in each column of the DataFrames
- Print the rows which have null values
- Calculate the most frequent value for each column

## Data Preprocessing
Once we have a good understanding of the data, the next step is to preprocess the data for analysis. The following tasks will be performed:

- Replace spaces in the column names with underscores
- Create a new column that includes both City and State in the ufo DataFrame
- Map existing values to different values in a specific column
- Convert the data type of a specific column to the datetime format
- Describe the information of all columns, numeric columns only, and object columns only
- Show the first 10 rows of the DataFrames
- Check if any row is identical to a previous row
- Count all duplicate rows in the DataFrames
- Show only duplicate rows in the DataFrames
- Drop all duplicate rows in the DataFrames
- Check for duplicates in a single specific column or multiple columns

## Data Visualization
The final step of the data analysis process is to visualize the data. We will use Matplotlib to visualize the following:

- Exploratory yearly analysis with dimensions on genres, revenue, and ratings
- Bar charts of genres with respect to revenue and average ratings.

By following the above steps, you will be able to perform comprehensive exploratory data analysis on the three datasets `ufo`, `u.user`, and `movies` using Pandas and Matplotlib.
