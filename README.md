# Fake News Detection Using Machine Learning

## Project Overview

This project is a Fake News Detection System developed using Python and Machine Learning. It classifies news articles as Real or Fake based on their content using Natural Language Processing (NLP) techniques.

## Features

* News Classification (Real/Fake)
* Text Preprocessing
* TF-IDF Vectorization
* Passive Aggressive Classifier
* Model Accuracy Evaluation
* Confusion Matrix Visualization
* Real-time News Prediction

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Natural Language Processing (NLP)

## Machine Learning Workflow

1. Load and preprocess the dataset
2. Combine title and text content
3. Convert text into TF-IDF features
4. Split data into training and testing sets
5. Train Passive Aggressive Classifier
6. Evaluate model performance
7. Predict whether news is Real or Fake

## Dataset

The dataset contains news articles with labels:

* REAL (1)
* FAKE (0)

## Results

* High classification accuracy using TF-IDF and Passive Aggressive Classifier
* Confusion Matrix visualization for performance analysis
* Detailed classification report including precision, recall, and F1-score

## Project Structure

fake-news-detection/
│
├── news.csv
├── fake_news_detection.py
├── README.md
└── requirements.txt

## Future Enhancements

* Deep Learning Models (LSTM/BERT)
* Web-based User Interface
* Real-time News Verification API
* Multilingual Fake News Detection

## Author

Tejaswi Lakshmi
