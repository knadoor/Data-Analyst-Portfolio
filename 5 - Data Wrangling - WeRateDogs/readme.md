# Data Wrangling - WeRateDogs

## Project Overview
This is the analysis of Twitter data as part of the Udacity Data Analyst Nanodegree program.

## Introduction
The datasets wrangled (and analyzed / visualized) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 8.9 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.

## Datasets
The following datasets were wrangled:

### Twitter-archive-enhanced.csv
This is a locally supplied file that contains 2356 records of tweets, all of which have ratings.

### Tweet_json.txt
The Twitter API was used to programmatically download the tweets as json data, the data we’re interested in is the retweet_count and favorite_count that is not available in the locally supplied file.

### Image_predictions.tsv
As above, this file was also programmatically downloaded.

Each of these data sets were loaded into individual data frames (df_archive, df_predictions and df_twitter) and separately cleaned – prior to merging all of them into a single data frame and outputting this as the final, cleaned dataset - twitter-archive-enhanced.csv.

## Data wrangling steps prior to conducting analysis included:
A total of 2 Tidiness and 15 Quality issues related to the data were identified and cleaned prior to exploring for insights.
