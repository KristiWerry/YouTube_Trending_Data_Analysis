# YouTube_Trending_Data_Analysis
## Team:

Kristi Werry - 823386935

William Ritchie - 815829203

## Description
This project analyzes YouTube trending videos between the years 2017-2018. We have data from Canada, Germany, France, England, India, Japan, South Korea, Mexico, Russia, and the US. We attempt to analyze these video to find which characteristics could make a video on YouTube trending. We look at relationships between views, likes, dislikes, the number of comments, keywords in the titles, descriptions, and tags, popular publish times, and popular trending dates of videos. Many of these characteristics and more contribute to a video's trending status. 

## Running the Program
To run this project you must have pandas, pyspark, and wordcloud installed. To install wordcloud: pip install wordcloud

The dataset can be downloaded from:

Dataset Kaggle link: https://www.kaggle.com/datasnaek/youtube-new

If you download the dataset from kaggle be sure to unzip and place it in folder called: youtube-new and ensure that this folder  is placed in the same directory as the .ipynb file. Alternatively the projects github also contains the dataset as well. 

GitHub Project link: https://github.com/KristiWerry/YouTube_Trending_Data_Analysis

## Defects
The last section in the notebook runs a calculation for pearsons correlation between a few of the columns.  For some reason after running that section we are un able to run some of the prior sections.  The solution to this is to restart the kernal and clear the output.
