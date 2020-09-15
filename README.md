This package eliminates outlier rows using interquartile range method(using 25th and 75th percentile of each coloumn of dataset).

Package has a function named elimrow which eliminates outlying rows.

You need to pass two parameters:
1. Input File Name
    The name of the file where actual dataset is present. (Target dataset)
2. Output File Name
    The name of the file where the data has after removing outliers has to be placed.

For example 
Name of input file is mydata.csv 
Output file name is newdata.csv

Parameters to be passed are
1. 'mydata.csv'
2. newdata.csv'