# Youtube API
Working with Youtube's API to collect channel and video statistics from 10 youtubers and upload the data to an AWS RDS Postgresql database to analyze with Power BI. 

**References:** 
1) [Python Project to Scrape YouTube using YouTube Data API | Analyze and Visualize YouTube data](https://www.youtube.com/watch?v=SwSbnmqk3zY)
2) [Importing a Pandas Dataframe to a Database in Python [For Your Data Science Project]](https://www.youtube.com/watch?v=77IVf0zgmwI)

## Background
I was looking to better understand what makes a youtube channel popular. I felt the best place to start was using Youtube API to collect the data using 10 channels from data analysts/scientists that I follow.

## Overview
## YT_Analysis_Project.ipynb
This script collects different kinds of data from Youtube API (channels and videos) to perform our analyisis.

## Youtubers Popularity.pbix
This Power BI file contains the dashboards used in our analysis to perform our insights that helped us to answer our question.

### Prerequisites
1) Python installed and environment with libraries used in our script
2) Create a Youtube API Key by going to [Youtube API signup](https://console.cloud.google.com/apis/).
3) Create a [AWS RDS Postgresql DB](https://aws.amazon.com/) to upload the data
