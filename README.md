# Exploratory-data-analysis-of-Drug

you can find the data sets in the link
https://archive.ics.uci.edu/ml/machine-learning-databases/00462/

here, in this project we analyze each an every coloum throughly.
this drug analysis consist of 7 columns, drugName,condition,review, rating,date and usefulcount.
i.e for "drugName" column i write some suffix for the name and classify them in class.
for "review" section of the drug i.e. commment i have done the sentmental analysis to view the comment and compare it with ratings. 
for "date" i just do do the time series analysis using the column like review, rating and usefulcount.
i analyze ratings, condition and usefulcount normally.


for carring out EDA libraries used:
import pandas as pd
import numpy as np

for visualization libraries used:
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline

for sentiment analysis
from textblob import TextBlob

questions generated?
how many types of drug we have?
what is the most popular drug?
what are the group\classification of drug use?
how many group of drugs by class?
How many drugs per condition
how many conditions are there?
which condition are the most common?
distribution of condition and ratings?
distribution of ratings?
average ratings per count?
which group of drug has highest men/average rating?
which drug has the highest ratings?
how genuine is the review (using sentiment analysis)?
how many positive negative and neutral review?
number of user who found review useful?
top usefulcount by drugs/drugs?
best drug on useful counts?
distribution on rating per year?
distribution of review per year?
amount of review per year?




