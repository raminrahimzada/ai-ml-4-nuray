# Pandas and Seaborn - Data Analysis and Visualization

## Topics

* Pandas
    - Series and DataFrames
    - read csv and json files
    - describing (info, head, tail)
    - cleaning (handling missing values isnull() dropna() fillna())
    - filtering / querying
    - grouping and aggregation
    - null / missing values stats
    - unique value counts value_counts() nunique()
    - dropping a column
    - adding new column

* Seaborn
    - lineplot() (Trends over time)
    - barplot() (Categorical comparisons)
    - scatterplot() (Relationships between variables)
    - histplot() (Histograms)
    - kdeplot() (Density curves)
    - boxplot() (Quartiles/outliers)
    - countplot() (Frequency counts)
    - violinplot() (Distribution + density)

## Resources
0. [Pandas 10 minute guide](https://pandas.pydata.org/docs/user_guide/10min.html)
0. [W3 Schools pandas](https://www.w3schools.com/python/pandas/default.asp)
0. [Seaborn example gallery](https://seaborn.pydata.org/examples/index.html)
0. [G4G Seaborn tutorial](https://www.geeksforgeeks.org/python/python-seaborn-tutorial/)

## Tasks

0. finish these micro courses
    - [Kaggle/Intro to programming](https://www.kaggle.com/learn/intro-to-programming)
    - [Kaggle/Python](https://www.kaggle.com/learn/python)
    - [Kaggle/Pandas](https://www.kaggle.com/learn/pandas)
    - [Kaggle/Data Visualization](https://www.kaggle.com/learn/data-visualization)
    
0. write a python function to return if a number is prime or not
0. write a python function that returns i-th prime number where i is its first and the only parameter
0. create a pandas DataFrame which contains the first N=100 prime numbers, so, columns will be "n"-> 1,2,3, ... N=100 and "p" -> 2,3,5, ... 541
0. find all the rows where prime number column ("p") is of the form 6*i + 1 (for example 7,13,19,31 ... )
0. find all the rows where the column "n" is also a prime number
0. save them to separate csv files (result of above 2 tasks)
0. use lineplot to visualize that first N=100 prime numbers
0. load titanic dataset using seaborn
0. find out how many males and females were in the ship
0. find out which gender is survived the most
0. find out which class is survived the most
0. find out which age is survived the most
0. find out who were the 3 youngest survivors
0. find out who were the 3 oldest survivors
0. extract title from Name column and create new column from title's  (	fyi: title is whether the person is Mr,Mrs, Miss etc.)
0. find out which title was the most
0. calculate percentage of survival based on 1. class, 2. gender, 3. age, 4. class+gender
0. fill missing age values with the median age by class
0. use boxplot to visualize fare distribution by class 
0. use countplot to visualize passengers by survival
0. use histplot to visualize passengers' age distribution
0. use heatmap to visualize heatmap survival rate by class and gender

### Note: 
please add descriptive titles to all plots in the tasks
and write a comment or text about the task itself before each code cell or group of cells
