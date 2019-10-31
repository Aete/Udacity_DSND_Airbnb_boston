# Udacity_DSND_Airbnb_boston

This repository is about analyzing Airbnb Boston dataset to establishing Medium post (URL: https://medium.com/@seunggyunhan/3-interesting-facts-about-airbnb-in-boston-b626cc8e4b8d)

## Objective

As one of customers in Airbnb, I was curious about important factors of prices and ratings. Therefore, I analyzed Airbnb Boston dataset as a project in Udacity Data Scientist Nanodegree. These are my 3 questions about Airbnb in Boston.
- Which factor had the highest correlation with ‘Price’?
- Which factor had the highest correlation with ‘Overall Rating’?
- Which zipcode got the best location score?

## Working Process

I tried to follow CRISP-DM framework to get some insights from the dataset. However, I didn’t make any model in this notebook, so my process contains front parts of CRISP-DM, but it doesn’t contain modeling, evaluation, and deployment parts. Here are the steps which I followed:
- Bussiness understanding: regarding business (Airbnb Boston), making meaningful questions and checking the resources what I have.
- Data Understanding: looking the dataset briefly like identifying features in the dataset and shape (size) of the dataset.
- Data Preperation: Cleaning the dataset (Removing missing values).
- Explore the dataset: exploring the dataset to get some insights about the questions in ‘Bussiness understanding’ part.

## Result
Here are 3 interesting facts corresponding to the 3 questions.
- There was moderate correlation (0.5<r<0.7) with the price and the capacity of Airbnb house. However, the other features had weak correlation with the price.
- Review scores of values, cleanliness, and accuracy impacted on the overall score more than the other scores.
- Based on the review scores of location, the zipcodes of 02446, 02445 could be better choice than the other areas. In addition to this, from a perspective of cost-effectiveness, the zipcoes of 02445 might be the best option.

## Files

1. Analyzing Airbnb boston.ipynb
Jupyter notebook that contains explanations and codes for analyzing Airbnb Boston Dataset.

2. Data
2.1 listing.csv
- Listings, including full descriptions and average review score
2.2 reviews.csv
- Reviews, including unique id for each reviewer and detailed comments
2.3 calendar.csv
- Calendar, including listing id and the price and availability for that day
