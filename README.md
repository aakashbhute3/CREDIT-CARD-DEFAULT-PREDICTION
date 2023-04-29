# Credit-Card-Default-Prediction

## Overview
This is a classification model for predicting credit card defaulters based on demographic and 6-month behavioral data. It involves collecting and preprocessing data, developing the model using various classification algorithms, evaluating its performance, and optimizing it for better risk management.

## Motivation
Many people have experienced the challenge of managing credit card debt, which can quickly spiral out of control due to high interest rates and other fees. Financial setbacks like job loss, medical emergencies, or business failure can make it difficult to keep up with payments. This is where a credit card defaulter prediction model can be useful for banks to assess the risk of lending to customers.

The model uses demographic data such as gender, age, and marital status, as well as behavioral data such as payment history and transaction patterns, to predict the likelihood of a customer defaulting on their credit card payments. By identifying high-risk customers, banks can take proactive measures to prevent financial losses.

Credit card debt is a common problem, and missed payments can quickly snowball into significant financial hardship. Predictive models can help identify potential problems before they become unmanageable, enabling banks to work with customers to find solutions and avoid default.

## Dataset Information
The dataset pertains to credit card clients in Taiwan from April 2005 to September 2005 and includes information on default payments, credit history, bill statements, demographic factors, and payment records.

## Technical Aspect
This project is divided into two part:
1. Training a [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) classification model to predict defaulter as accurate as possible.
	- Cleaning the datasets, fixing all features
	- Apply Classification ML model
2. Building and hosting a Flask web app on Heroku.
	- Build the web app using Flask API
	- Upload the project on GitHub
    - Get the customer information from Web app
    - Display the prediction 

## Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```


## Credits
- The datasets has been provided by [Kaggle](https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset). 
