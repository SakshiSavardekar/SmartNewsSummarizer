A Smart News Summarizer is capable of summerizing the big news articles into smaller paragraphs and correctly categories them into different categories.

* Technologies used:

1) News API provided by NewsData.io for fetching real and latest news articles
2) Newspaper3k library for extracting text from the news articles
3) Facebook Bart Model provided by Hugging Face for summarizing the news articles
4) Logistic Regression Model for classifying the news into different categories
5) News Category Dataset from Kaggle for training the Logistic Regression Model

* How to execute?

1) Download the News Category Dataset from Kaggle (Link is provided in the notebook)
2) Unzip it, rename it as "newsData.json" and upload it to the "sample_data" folder on Google Colab
3) Run the notebook
4) After execution, two PDFs will be genearted.
    1. original_news.pdf : contains original news extracted from the articles along with thier title
    2. summarized_news.pdf : contains summarized version of all the news, each categorized as per their appropriate categories.
