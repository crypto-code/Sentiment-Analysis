# Sentiment-Analysis
Use NLP to train a Naive Bayes Classifier to Analyse Sentiment in Text

<p align="center">
<img src="https://github.com/crypto-code/Sentiment-Analysis/blob/master/assets/model.png" align="middle" />   </p>

## Naive Bayes Classifier

A Naive Bayes classifier is a probabilistic machine learning model that’s used for classification task. The crux of the classifier is based on the Bayes theorem.

<p align="center">
<img src="https://github.com/crypto-code/Sentiment-Analysis/blob/master/assets/bayes_theorem.jpg" align="middle" />   </p>

Using Bayes theorem, we can find the probability of A happening, given that B has occurred. Here, B is the evidence and A is the hypothesis. The assumption made here is that the predictors/features are independent. That is presence of one particular feature does not affect the other. 

Naive Bayes algorithms are mostly used in sentiment analysis, spam filtering, recommendation systems etc. They are fast and easy to implement but their biggest disadvantage is that the requirement of predictors to be independent. In most of the real life cases, the predictors are dependent, this hinders the performance of the classifier.

## Prerequisites
- NLTK (https://pypi.org/project/nltk/)
- To download the required from nltk package run the following in Python IDLE,
```
>>> import nltk
>>> nltk.download('twitter_samples')
>>> nltk.download('punkt')
>>> nltk.download('wordnet')
>>> nltk.download('averaged_perceptron_tagger')
```

## Usage

- To train the Classifier run,
```
python nlp_train.py
```
**Note: This will create a pickle file to store the trained model, one already has been provided if you want to skip this step.**

- To test the Classifier run,
```
python nlp_test.py
```
**Note: This will create an interactive prompt where you can enter the scentences to classify.**

## Examples

```
> The coffee I drank is soooo bad
The coffee I drank is soooo bad Negative
> Congrats. You look amazing.
Congrats. You look amazing. Positive
> The weather is terrible no one should be outside.
The weather is terrible no one should be outside. Negative
```


# G00D LUCK

For doubts email me at:
atinsaki@gmail.com
