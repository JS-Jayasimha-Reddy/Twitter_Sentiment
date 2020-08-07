# *Twitter Sentiment*
> App that predicts the nature of the tweets and label them as "Positive" or "Negative"

## Table of contents
* [General info](#general-info)
* [Model lifecycle](#model-lifecycle)
* [Screenshots of app](#screenshots-of-app)
* [Screenshots of code](#screenshots-of-code)
* [Technologies Used](#technologies-used)
* [Setup](#setup)
* [Contact](#contact)

## General info
This app determines if a Tweet/sentence is positive or negative/hate speech. Though any general sentence can be used,the title is named "Twitter Sentiment" as the model is 
trained on the tweets from twitter. Hence,the sentiment could be a little biased on how it is perceived on twitter platform.

## Model Lifecycle
The Standard datascience lifecycle was followed for building this model.
1. **Business understanding**- The objective is to determine if a tweet is positive or negative
2. **Data collection**- Dataset acquired from [Kaggle](https://www.kaggle.com/kazanova/sentiment140),the original dataset of 1.6 million tweets were reduced to a random sample of 50000 tweets due to computing limitations
3. **Data preprocessing/Preparation**- Several steps were performed to clean the data like removing dublicates, punctuations,stop words etc
4. **EDA**- Used plots like Word cloud to understand more about the data
5. **Modelling**- Used Naive bayes model with Hyperparameter tuning and roc-auc as the metric
6. **Evaluation**- Used AUC plot and AUC score of test and train data to determine the effectiveness of the model.This was double checked by a confusion matrix
7. **Deployment**- Model was deployed using Streamlit and on AWS server --Click [HERE](http://18.191.219.195:8501) for the demo

## Screenshots of app
#### 1. 
<img src="https://github.com/JS-Jayasimha-Reddy/twitter_sentiment/blob/master/Images/tweet2.PNG">

#### 2.
<img src="https://github.com/JS-Jayasimha-Reddy/twitter_sentiment/blob/master/Images/tweet1.PNG">


## Screenshots of code
<img src="https://github.com/JS-Jayasimha-Reddy/twitter_sentiment/blob/master/Images/note1.PNG">
<img src="https://github.com/JS-Jayasimha-Reddy/twitter_sentiment/blob/master/Images/note2.PNG">
<img src="https://github.com/JS-Jayasimha-Reddy/twitter_sentiment/blob/master/Images/note3.PNG">



## Technologies Used
* Tech 1 - version 1.0
* Tech 2 - version 2.0
* Tech 3 - version 3.0

## Setup
Describe how to install / setup your local environement / add link to demo version.

## Future Scope
Project is: _in progress_, _finished_, _no longer continue_ and why?

## Contact
