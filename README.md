# YouTube Sentiment Analysis
## 📌 Overview

This project performs sentiment analysis on YouTube comments using the YouTube Data API v3. The goal is to extract user opinions from a selected video and analyze them using natural language processing techniques.

### 📊 Dataset
* Source: YouTube Data API v3
* Video: https://www.youtube.com/watch?v=ix9cRaBkVe0
* Total comments analyzed: 200
### ⚙️ Features
* YouTube API integration for comment extraction
* Text cleaning and preprocessing
* Stopwords removal using NLTK
* Sentiment analysis using:
  - TextBlob (polarity-based)
  - NaiveBayesAnalyzer (probabilistic model)
* Model comparison between TextBlob and Naive Bayes
* WordCloud visualization of frequent terms
### 📦 Libraries Used
* google-api-python-client
* pandas
* textblob
* nltk
* matplotlib
* wordcloud
### 📈 Results
* Most comments are neutral to positive
* TextBlob provides fast polarity-based classification
* NaiveBayesAnalyzer shows slightly different sentiment distribution
* WordCloud highlights common discussion topics in comments
### 📌 Key Insights
* YouTube comments are often short and informal
* Many comments contain repetitive or non-informative text
* Sentiment analysis helps summarize overall audience reaction
