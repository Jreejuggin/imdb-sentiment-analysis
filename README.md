# imdb-sentiment-analysis
Analysis of IMDB Dataset of 50K Movie Reviews using Convolutional Neural Networks (CNNs)
# IMDB Dataset of 50K Movie Reviews

## Overview
This project uses Convolutional Neural Networks to classify a positive or negative IMDb movie review.

## Dataset
IMDB dataset has 50K movie reviews for natural language processing or Text analytics.
This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training and 25,000 for testing. So, predict the number of positive and negative reviews using either classification or deep learning algorithms.
For more dataset information, please go through the following link,
http://ai.stanford.edu/~amaas/data/sentiment/

## Methods
A sequential model is used to add multiple layers to the network. The CNN consists of five layers: an embedding layer, a 1D convolutional layer, a pooling layer, and two fully connected layers. The embedding layer serves as the input stage. The convolutional layer then extracts local features from the embedded layer, which are then reduced in dimensionality by the pooling layer. The final two fully connected layers combine the extracted features and produce the model’s prediction.

## Results
Accuracy obtained: 90%

## Technologies Used
- Python
- NumPy
- Pandas
- scikit-learn
- TensorFlow/PyTorch
- Matplotlib
