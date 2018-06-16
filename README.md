# WeRateDogs - Data Wrangling

## Overview

Gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. Showcase your wrangling efforts through analyses (Udacity).

The dataset that we will be wrangling is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. 

## Description 

### The Data

There are three Pandas dataframes used in this analysis:

* An enhanced Twitter archive provided by Udacity . This dataset contains basic tweet data for more than 2000 tweets. The tweet text was used to extract ratings, dog names and dog stages. This file was downloaded manually from Udacity's website and saved as 'tarchive'.

* Data obtained by query Twitter API, using Python's Tweepy library. This contains each tweet's retweet count and favorite ("like") count. This is saved as 'tweets_df'.

* Results obtained by running a neural network on the Twitter archive in order to predict what breed of dog is present in each tweet. The file is hosted on Udacity's servers and was downloaded programmatically using the Requests library. It was saved as 'img_preds'.


### The Reports

The file _wrangle_report.html_ that describes in detail the wrangling efforts. These are performed in Python 3, using Pandas and NumPy.

The file _act_report.html_ communicates the insights and displays the visualization(s) produced from your wrangled data. 
