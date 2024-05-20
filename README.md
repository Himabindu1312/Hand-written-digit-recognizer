# MNIST Digit Classification using K-Nearest Neighbors (KNN)

This repository contains a Python implementation for classifying handwritten digits from the MNIST dataset using the K-Nearest Neighbors (KNN) algorithm. The dataset is downloaded from Kaggle and processed using Pandas and NumPy, and the KNN model is implemented both manually and using scikit-learn.

## Overview

The goal of this project is to classify images of handwritten digits (0-9) from the MNIST dataset using K-Nearest Neighbors (KNN). We first implement the KNN algorithm from scratch and then use the `KNeighborsClassifier` from scikit-learn for comparison. The performance of the model is evaluated using a confusion matrix and accuracy score.

## Dataset

The MNIST dataset contains 60,000 training images and 10,000 test images of handwritten digits. Each image is 28x28 pixels.

## Results
The scikit-learn KNN model achieved an accuracy of approximately 96.97% on the test set. The confusion matrix is printed to show the classification performance for each digit.
