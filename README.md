# Sentiment Analysis Project

## Overview

This project focuses on sentiment analysis, a natural language processing task aimed at determining the sentiment expressed in textual data, whether it's positive, negative, or neutral. Sentiment analysis has various applications, including social media monitoring, customer feedback analysis, and market research.

## Dataset

The dataset used for this project is sourced from Kaggle and contains tweets labeled with sentiments. You can access the dataset [here](https://www.kaggle.com/datasets/kazanova/sentiment140/data).

## Techniques Implemented

The sentiment analysis task is approached using two different techniques:

1. **Logistic Regression**: A traditional machine learning algorithm used for binary classification tasks.
2. **Long Short-Term Memory (LSTM)**: A type of recurrent neural network (RNN) suitable for processing and classifying sequential data.

## Notebooks

The project includes two Jupyter notebooks:

- `Logistic_Regression_Sentiment_Analysis.ipynb`: Implements sentiment analysis using logistic regression.
- `LSTM_Sentiment_Analysis.ipynb`: Implements sentiment analysis using LSTM.

## Evaluation Metrics

Evaluation of the models is based on various metrics, including accuracy, precision, recall, F1 score, and confusion matrix.

## Model Files

The trained models are saved in the `models/` directory:

- `LogisticRegression_trained_model.sav`: Trained logistic regression model.
- `lstm_model.h5`: Trained LSTM model.

## Requirements

To run the notebooks and scripts, make sure to install the necessary dependencies listed in the `requirements.txt` file.

## Usage
- download the csv file and paste it into the folder link - [here](https://www.kaggle.com/datasets/kazanova/sentiment140/data).

- clone the repo - ``https://github.com/as-repo1/Sentiment-analysis?tab=readme-ov-file``
- install the packages - ``pip intstall -r requirements.txt``
- run the notebooks using jupyter-notebook or any ide of your choice
