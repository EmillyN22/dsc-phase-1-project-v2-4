PHASE 1 PROJECT

Microsoft has decided to start creating video content by starting a new movie studio.
In this project we explore what types of films are currently doing the best in the box office and translate the findings into actionable insights.

I use two data sets. The im.db database and bom.movie_gross.csv file.
I import the libraries required to data clean these data sets.

# for data manipulation
import pandas as pd 
# for numeric computation
import numpy as np 
# for ploting our data and creating visualization
import matplotlib.pyplot as plt 
%matplotlib inline
import sqlite3

# Connect to the SQL database
conn=sqlite3.connect('im.db')
cur=conn.cursor()

we clean these data sets by checking for missing values and dropping them.
# checking for missing values
data.isna().sum()
# dropping missing values
data.dropna(inplace=True)

