# Repo for sentiment analysis on Alexa reviews

1. Built a simple model that analyses the sentiment of the reviews. It helps the companies to understand the customers take on the products.
2. Cleaned the data and performed EDA to get a better understanding of the data.
3. Used NaiveBayes and logistic regression model to get prediction result of 93% accuracy.

## Code and Resources used

Python Version: 3.7

Packages: pandas, numpy, sklearn, matplotlib, plotly, nltk, wordcloud, pillow, string

Dataset : Kaggle

## Model Building

* Cleaned the data by removing punctuations and stopwords.
* Performed Tokenization/Count vectorization of texts.
* Transformed the categorical variables into dummy variables. Split the data into train and tests sets with a train size of 80%.
* Tried two different models and evaluated them using F1 score.
* Chose F1 score because F1 Score is more useful than accuracy, especially in an uneven class distribution.

## Visualizations

#### Funnel chart 

![alt text](https://github.com/Jishan-works/Sentiment-analysis-for-alexa-reviews/blob/master/funnel_chart.png)

#### Positive Word cloud

![alt text](https://github.com/Jishan-works/Sentiment-analysis-for-alexa-reviews/blob/master/positive_text_wc.png)

#### Positive Treemap

![alt text](https://github.com/Jishan-works/Sentiment-analysis-for-alexa-reviews/blob/master/treemap_positive.png)

#### Negative Treemap

![alt text](https://github.com/Jishan-works/Sentiment-analysis-for-alexa-reviews/blob/master/treemap_negative.png)

## Model Performance

Both the NaiveBayes and Logistic Regression model performed on the same level on the test data.

| Model                | Accuracy       |
| ---------------------|:--------------:|
| NaiveBayes           | 94.44 %        |
| Logistic Regression  | 95.39 %        |







