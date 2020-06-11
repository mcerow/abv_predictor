# Predicting ABV in Craft Beers
Maura Cerow

## Introduction

This project aims to predict the ABV level in a given craft beer using linear regression. The data was found on [kaggle](https://www.kaggle.com/neuromusic/avocado-prices/data).

The libraries used include:

    - NumPy
    - Pandas
    - Matplotlib
    - Seaborn
    - Sklearn
    - Scipy
    - Statsmodels

In this repo you will find my jupyter notebook, csv file from kaggle and folder for images of visualizations made.

## Data Cleaning & Modeling

    see: Blog3.ipynb
    
After reading in my data, I wanted to check the distribution of my target variable which in this case is ABV level.

![](images/ABV_Dist.png)

I have some outliers in my data, so I want to drop those. I use my interquartile range to cut outliers on both ends of my dataset.

Now that I have my clean data, I checked for correlation between my target variables and the features I'll be using in modeling. IBU has the highest correlation with ABV at .65.

