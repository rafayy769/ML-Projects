<!-- Readme file for Machine Learning projects. -->
# Projects
This repository contains Machine Learning projects that I have worked on. The projects are listed below:
## kNN Classification
The project builds a digit classifier using the k-Nearest Neighbors algorithm. The classifier is trained on the MNIST dataset of handwritten digits. The classifier is then tested on a test set of 10,000 images. The classifier achieves an accuracy of 95.9% on the test set. The project also explores cross-validation and the effect of different values of k on the accuracy of the classifier, and thus is a thorough exploration of a basic machine learning pipeline. The project is implemented in Python and makes use of JIT extensively to build a fast classifier.

## Linear and Logistic Regression
The project builds a linear regression model and a logistic regression model from scratch.
### Multivariate Linear Regression
We explore the Boston Housing dataset and build a linear regression model to predict the price of a house given its features. We also explore the effect of different values of the regularization parameter on the model.
### Logistic Regression
We build a Machine Learning Model using Logistic Regression to do some sentiment analysis. A dataset of 50,000 movie reviews is used. The goal is to predict whether a given review is positive or negative.

## Neural Networks
The project builds a neural network from scratch. The goal is to use the MNIST audio dataset to build a neural network that can classify digits. After implementing the model from scratch, implementations using tensorflow Keras and PyTorch are also explored.

## Naive Bayes
### Text generation using Naive Bayes
The project builds a text generator using the Naive Bayes algorithm. We are working with Urdu Language.
### Text classification using Naive Bayes
The project builds a text classifier using the Naive Bayes algorithm. We are working with the AG News dataset. The goal is to classify news articles into 4 categories: World, Sports, Business, and Sci/Tech.