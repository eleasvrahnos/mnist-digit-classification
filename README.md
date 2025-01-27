# MNIST Digit Classification

Author: Eleas Vrahnos

## Overview to ML and CNNs

Machine Learning is a subset of artificial intelligence that focuses on creating models, allowing computers to do things like make predictions and decisions. These systems learn from data and improve their performance over time. ML is widely used in various applications, including image/handwriting recognition (this project), natural language processing, and predictive analytics. One more thing to note is that ML models can be supervised, unsupervised, or semi-supervised, depending on the type of data and the learning task at hand.

Convolutional Neural Networks (CNNs) are a class of deep neural networks specifically designed for processing structured grid data, which makes it perfect for data like images since they are really just a grid of pixel color values. CNNs use a series of convolutional layers and fully connected layers to learn spatial hierarchies of features from input images (such as corners and circles from reading digits). This makes them highly effective for tasks like image classification, object detection, and segmentation.

## Interest in ML

My interest in ML stems from their huge potential in various fields, including computer vision, healthcare, and autonomous systems. We see it everyday now, from advertisement predictions to image recognition. The ability of these technologies to learn from data and make intelligent decisions fascinates me, and I wanted to understand how they work under the hood a bit better. This project aims to act as a "Hello World" introduction to the world of ML training and CNNs.

## Project Overview

This project focuses on the classification of handwritten digits using the MNIST dataset. The MNIST dataset is a well-known benchmark in the field of machine learning, consisting of 60,000 training images and 10,000 testing images of handwritten digits (0-9). The goal of this project is to build a Convolutional Neural Network (CNN) that can accurately classify these digits. It is by no means perfect, but it still taught me a lot about what ML entails.

### Key Steps in the Project:

1. **Data Preparation**: Loading and preprocessing the MNIST dataset, including normalization and reshaping of images.
2. **Model Creation**: Building a CNN with multiple convolutional, activation, and pooling layers to extract features from the images.
3. **Training**: Training the CNN on the training dataset and validating its performance.
4. **Evaluation**: Testing the trained model on the testing dataset to evaluate its accuracy.
5. **Prediction**: Using the trained model to predict digits from custom images.
6. **Application**: Using the model to read handwritten digits in real time.
