# Fox News Articles Data Analysis

## Objective
The primary goal of this project is to perform comprehensive data analysis on news articles from Fox News. This involves web scraping to collect data, followed by data cleaning, exploratory data analysis (EDA), sentiment analysis, and network analysis. The project aims to provide insights into the content and structure of the news articles, identify prominent topics, analyze sentiment, and examine the relationships between different categories of news.

## Data Collection
Data is collected through web scraping from the Fox News website. The key fields extracted for each news article include:
- **Title:** The headline of the news article.
- **Link:** The URL of the article.
- **Corpus:** The main text or content of the article.
- **Category:** The section/category to which the article belongs (e.g., politics, sports).
- **Author:** The author of the article.
- **Time and Date:** The publication date and time of the article.

## Data Cleaning
The collected data undergoes several cleaning steps:
- Removing unnecessary prefixes (e.g., "By") and suffixes from author names as well.
- Standardizing time zones in the date column.
- Removing unwanted patterns and sponsored content from author names.
- Handling missing values by dropping rows with any missing data.

## Exploratory Data Analysis (EDA)
EDA involves visualizing the distribution of articles across different categories, analyzing the length of articles, and examining the publication trends over time. Key steps include:
- Plotting the number of articles per category.
- Analyzing the word count distribution in the corpus.
- Visualizing publication dates to identify trends and peaks in article publishing.

## Sentiment Analysis
Sentiment analysis is conducted to determine the emotional tone of the articles. Using TextBlob, each article's polarity (sentiment score) and subjectivity are calculated. This helps in:
- Classifying articles as positive, negative, or neutral based on sentiment score.
- Analyzing the overall sentiment distribution across different categories.

## Network Analysis
Network analysis is used to study the relationships and interactions between different categories of news articles. Key steps include:
- Building a graph where nodes represent categories and edges represent shared topics or keywords.
- Calculating centrality measures (degree) to identify key categories.
- Visualizing the network to understand the structure and central nodes.

## Conclusion
The project provides a thorough analysis of Fox News articles, offering insights into the content, sentiment, and relationships between different news categories. The combination of various data analysis techniques allows for a comprehensive understanding of the news landscape and helps in identifying key trends and patterns in the data.




## Navigate through the numbers turn wise 
