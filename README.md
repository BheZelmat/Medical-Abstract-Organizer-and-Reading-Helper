# Medical-Abstract-Organizer-and-Reading-Helper




![alt text](https://github.com/BheZelmat/Medical-Abstract-Organizer-and-Reading-Helper/blob/main/Img.png?raw=true)



This project presents a comprehensive solution to assist in organizing and understanding medical publications' abstracts using advanced natural language processing (NLP) techniques. Built with Python and leveraging TensorFlow, the system preprocesses, analyzes, and classifies abstracts into their respective sections, such as OBJECTIVE, METHODS, RESULTS, and CONCLUSIONS, making it easier to digest and analyze scientific articles.

## Features

* Text Preprocessing and Data Preparation: Implements techniques for cleaning and preparing text data for analysis.
* Model Implementation: Uses TensorFlow and TensorFlow Hub for implementing LSTM models and leveraging pre-trained embeddings for text representation.
* Sentiment Analysis: Includes a Naive Bayes TF-IDF baseline for comparative analysis.
* Custom LSTM Model: Custom-built LSTM model with Tribrid Embedding designed to understand the structure and content of medical abstracts.
* Performance Evaluation: Evaluation metrics including accuracy, precision, recall, and F1 score to gauge model performance.

## Usage

* Data Preparation: Preprocess the medical abstracts using the provided scripts to convert raw text into a structured format.
* Model Training: Train the LSTM model using the prepared dataset, adjusting parameters as necessary to improve performance.
* Evaluation: Assess the model's performance with the included evaluation metrics.
* Application: Apply the trained model to new abstracts for classification and analysis.

## Requirements

Python 3.x
TensorFlow 2.x
TensorFlow Hub
Pandas
NumPy
Scikit-Learn
Matplotlib

## Usage
The document includes code snippets and explanations for each step of the NMT system development. You can replicate the process, train the model with the provided dataset, and test its organization capabilities on new data.

## Author
Houssem Zelmat 
