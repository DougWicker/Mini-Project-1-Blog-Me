# Mini Project 1 - BlogMe

#### Project brief:
The project brief was as follows: BlogMe, a famous blogging business has a dataset of news articles that they need further analysis on. Firstly, they’d like keywords to be extracted from the headlines of the article. Secondly, they would need to determine the sentiment of the news articles. The data is in an Excel sheet and they would like to see a dashboard for outlying sentiment, top articles etc.

___

In order to satisfy the project brief, I will need to process and manipulate the dataset using the Pandas library in Python, use a Natural Language Processing library called 'Vader' to perform sentiment analysis, and finally extract the data to Tableau and create an interactive dashboard.

Here's a summary of what my Python code will need to do:

1. Import the necessary libraries and classes: pandas and SentimentIntensityAnalyzer from vaderSentiment.vaderSentiment.
2. Read an Excel data source file named and store the data in a DataFrame.
3. Generate summary statistics and determine metrics such as the number of articles by source and the number of reactions by publisher using groupby operations.
4. Perform any required wrangling / cleaning of the dataset.
5.  Flag articles based on a keyword.
6.  Use sentiment analysis to analyse the sentiment of the article headers to determine how positive, neutral or negative they are.
7.  Output the cleaned data ready to import into Tableau

In summary, the code will need to read the CSV file, transform it into a DataFrame, clean and wrangle the data and perform sentiment analysis, and export the modified data frame to a CSV file.

Below is the dashboard that I created with the cleaned dataset:  
[Link to Interactive Dashboard](https://public.tableau.com/app/profile/douglas1371/viz/BlogMeArticleAnalysis_16874562939960/BlogMeNewsDashboard)
![BlogMe News Dashboard](https://github.com/DougWicker/Mini-Project-1-BlogMe/blob/7cd3d41e4c6ff743d151bfd6dc6d67cb827789ad/BlogMe/BlogMe%20News%20Dashboard.png)

This project was part of a Data Analysis Bootcamp, hosted on Udemy and Created by Dee Naidoo, and contributed to the following certificate:
![Certificate of Completion](https://github.com/DougWicker/Mini-Project-1-BlogMe/blob/7cd3d41e4c6ff743d151bfd6dc6d67cb827789ad/Bootcamp%20Certificate.jpg)

