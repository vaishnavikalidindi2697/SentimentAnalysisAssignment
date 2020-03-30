
## The topic of the Assignment given:

Each review is associated with a medicine name. But the reviews provided by the users are complex in nature and some reviews contain information about multiple medicines as well. 

For example:

Medicine A review : “It works well on fever. Medicine A is better than Medicine B”.

The overall review is positive for Medicine A, but it is negative for Medicine B. 
Your task is to build an Sentiment Analysis model. It should have following feature: 

● For a given medicine, your model should classify review as Positive, Negative or Neutral.

● It should generate sentiment scores based on overall data i.e. incorporating the complex reviews information.

## Approach used for the Assignment:

The approach used for this assignment is as follows:

* Importing the datasets
The datasets given were imported into the python environment using the pandas package.

* NLP Pipeline:
The steps that are included in the NLP pipeline is done using
a. NeatText Package - For the process of removing numbers, email addresses, phone numbers, special characters, emojis, stopwords etc. 
b. NLTK Package - For the process of stenning and parts of speech tagging.

* Data Visualization:
The data visualization for the reviews, drugs and the sentiments is done using the matplotlib, seaborn and wordcloud packages.

* Polarity and Subjectivity:
Polarity and Subjectivity are two most important things to undestand the reviews that are given to us. Polarity is the level of the sentiment in the text and Subjectivity is the level of the reviewers opinion in the text. These both influence the polarity i.e. Positive, Neutral or Negative, of the text.

To find out the polarity and subjectivity of all the reviews, TextBlob package is used.

## Best Approach to solve the Assignment:

The reviews given the datasets are comparitve in nature. The best way to analyse the sentiments of comparitve opinions is to used "Aspect Based Sentiment Analysis". 

In Aspect based Sentiment Analysis, the two different kinds of medicines given in the reviews are taken as two seperate aspects.

We can then use the opinion extractors to extract different opinions regarding different aspects from one review and then assign a polarity score, with help of which we can decide the sentiment that is positive, neutral are negative.

In this Aspect Based Sentiment Analysis, we can use models like BERT to develop a model which classifies the sentiment accurately given a medicine name.


```python

```
