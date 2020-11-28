# Data mining project for K6312
## What did media say when talking about COVID-19: Analysis of topics and sentiments of COVID-19 news headlines

### Background
* The COVID-19 virus has spreaded around the world and has a wide-ranging impact on society.
* The COVID-19 pandemic has received worldwide public concern.
* Countless articles on COVID-19 presented in public media, and media plays an important role in shaping people’s attitudes towards COVID-19.

### Objectives
* Sentiment analysis: What are the sentiments of the news headlines?
* Topic analysis: What are the most common topics discussed based on news headlines?
* Sentiment-based topic analysis

### Dataset
* Kaggle Dataset - Covid-19 Public Media Dataset
* 290,000+ articles crawled from 20+ high-impact blogs and news websites
* From 2020-01-02 to 2020-09-14
* Covering topic areas of general news, finance, science, technology...
* Columns of ‘title’, ‘date’, ‘content’, ‘author’, ‘topic_area’...
* Source url: https://www.kaggle.com/jannalipenkova/covid19-public-media-dataset


* IMDB dataset (for training sentiment models), retrieved November 22, 2020, from http://www.imdb.com/interfaces/

### Code file
* sentiment_analysis_binary_classification.ipynb - Preprocessing IMDB data; train Machine Learning approaches and test; select a sample of Covid-19 news dataset and annotate it manually; evaluating model's performance on the out-of-distribution set; use a good performing model strategy to label all data.
* sentiment_analysis_binary_classification_CNN.ipynb - Do sentiment classification with CNN based on IMDB dataset and test performance. 
* sentiment_analysis_binary_classification_vader.ipynb - Do sentiment classification with Vader based on IMDB dataset and test performance. 
* Testing_sentiment_analysis_binary_classification.ipynb -  Try to train the model on the News Popularity in Multiple Social Media Platforms Dataset.
    (But after comparing the results, the models performed better on the IMDB data and hence it was not used.)


* preprocessing_COVID_news_ipynb（for_topic_modeling）.ipynb - Preprocessing Covid-19 news data; cut data by month.
* topic_modelling_COVID_news_ipynb（for_topic_modeling）.ipynb - Use LDA to model topics.
* topic_classification_ipynb（for_topic_classification）.ipynb - Use Multinomial NB to classify topics.


* data_analysis_pandas.ipynb - Do topic, sentiment, and sentiment-based analysis.

### Data files used and generated
* Most data files are too large to upload.

### Additional notes
We have also attempted to train the model on the News Popularity in Multiple Social Media Platforms Data Set.
https://archive.ics.uci.edu/ml/datasets/News+Popularity+in+Multiple+Social+Media+Platforms
However, as seen in the comparison between Testing_sentiment_analysis_binary_classification.ipynb and Sentiment_analysis_binary_classification.ipynb, the dataset performed better on the IMDB data and hence it was not used.


Slides of our presentation can also be found here.

