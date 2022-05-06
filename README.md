# Emotion Classification 
`COMP 562 Final Group Project`

Authors: Rico Pojol, Kelsey Fauntleroy, Shuang Du, Minhui Yu

## Abstract
The goal of this project is to be able to classify the emotion behind a given text, so a computer or another person can take an appropriate action based on the resulting emotion from the classifier. We used a dataset of pre-processed English Twitter posts [2], each already labeled with one of six emotions: sadness, anger, love, joy, fear, and surprise. The dataset was already split into test, training, and validation sets. To classify the dataset, we tried different classical supervised machine learning models as well as the BERT NLP model, and calculated the accuracy on the test set for each model.

## Data Processing
Transform raw text [code](final.ipynb)

## Methodologies
Experiments with Classical Machine Learning Models (Multinomial Naive Bayes Classifier, Multinomial Logistic Regression, KNN, CART, SVM, LSTM with Tensorflow) [code](https://github.com/ReneeDu320/Emotion-Classification/blob/main/Tensorflow%20ml%20model.ipynb)

Experiments with State-of-the-art NLP Models (BERT) [code](https://github.com/ReneeDu320/Emotion-Classification/blob/main/BERT%20pytorch%20bert-base-case-3.ipynb)

## Data Source
The dataset used in this project is "Fake or Real News" from Kaggle. Link to the dataset: https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp

## Report
The project report can be found at [final report](Emotion_Classification.pdf)

