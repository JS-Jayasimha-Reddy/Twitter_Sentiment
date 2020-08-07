# *Twitter Sentiment*
> App that predicts the nature of the tweets and label them as "Positive" or "Negative"

## Table of contents
* [General info](#general-info)
* [Model Building](#model-lifecycle)
* [Screenshots](#screenshots)
* [Technologies Used](#technologies-used)
* [Setup](#setup)
* [Features](#features)
* [Contact](#contact)

## General info
This app determines if a Tweet/sentence is positive or negative/hate speech.Though any general sentence can be used,the title is named "Twitter Sentiment" as the model is 
trained on the tweets from twitter.Hence,the sentiment could be a little biased on how it is perceived on twitter.

## Model Lifecycle
The Standard datascience lifecycle was followed for building this model.
1. **Business understanding**- The objective is to determine if a tweet is positive or negative
2. **Data collection**- Dataset acquired from [Kaggle](https://www.kaggle.com/kazanova/sentiment140)
3. **Data preprocessing/Preparation**- Several steps were performed to clean the data like removing dblicates, punctuations,stop words etc
4. **EDA**- Used plots like Word cloud to understand more about the data
5. **Modelling**- Used Naive bayes model with Hyperparameter tuning and roc-auc as the metric
6. **Evaluation**- Used AUC plot and AUC score to determine the effectiveness of the model.This was double checked by a confusion matrix
7. **Deployment**- Model was deployed using Streamlit and on AWS server --Click [HERE](http://18.191.219.195:8501) for the demo

## Screenshots


## Technologies Used
* Tech 1 - version 1.0
* Tech 2 - version 2.0
* Tech 3 - version 3.0

## Setup
Describe how to install / setup your local environement / add link to demo version.

## Features
List of features ready and TODOs for future development
* Awesome feature 1
* Awesome feature 2
* Awesome feature 3

## Future Scope
Project is: _in progress_, _finished_, _no longer continue_ and why?

## Contact
