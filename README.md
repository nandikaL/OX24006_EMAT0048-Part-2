# OX24006_EMATM0048 Summative Assesment Part 2

## Exploratory Analysis of Skincare Subreddits

#### This is an exploratory analysis of webscrapped data from 6 different skincare subreddits: 

The subreddits used were r/SkincareAddcition with 4.3m members r/AsianBeauty with 2.9m members, r/30PlusSkinCare with 2.1m members, r/SkincareAddictionUK with 484k members, r/IndianSkincareAddicts with 242k members, r/AusSkincare with 177k members.  

Webscrapping was done using a reddit specific crawler. A list of ingredients and a list of concerns were generated. Amongst the top 1000 posts of each subreddit, posts which mention either these ingredients or concerns were collected and put into a pandas data frame. 

The data set from the dataframe was then analysed using descriptive statistics and visualized with plotting packages to answer a question about the data sets. Full explaination of the exploratory analysis is found in the markdown cells of the notebook.

## Installing and running the project 

#### For the analysis, the following libraries were used: 
- pandas
- matplotlib
- seaborn
- numpy

#### Additional packages used were: 
- PRAW (Python Reddit API Wrapper) for crawling reddit 
- NLTK for simple sentiment analysis 

#### Other modules/collections:
- datetime - to extract the time from the html timestamp
- colourcet - when specific palettes were wanted for graphs
