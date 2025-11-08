MNIST Handwritten Digit Classification

Using ANN and CNN (TensorFlow/Keras)

This project builds and compares two deep learning models — an Artificial Neural Network (ANN) and a Convolutional Neural Network (CNN) — for classifying handwritten digits from the MNIST dataset.

Project Overview

The MNIST dataset contains 70,000 grayscale images of handwritten digits (0–9), each sized 28×28 pixels.
The objective of this project is to correctly classify these digits using machine learning and deep learning techniques.

This notebook includes:

Data loading and preprocessing

Visualization of sample images

ANN model implementation

CNN model implementation

Training with early stopping

Accuracy and loss plots

Model evaluation and comparison

Models Used
1. Artificial Neural Network (ANN)

A simple baseline model consisting of:

Flatten layer

Dense layer with ReLU activation

Dense output layer with softmax activation

Validation Accuracy: approximately 97.6%

2. Convolutional Neural Network (CNN)

A more advanced model designed for image recognition, consisting of:

Convolutional layers

MaxPooling layers

Dropout to reduce overfitting

Dense layers for classification

Validation Accuracy: approximately 99.0%

The CNN performs significantly better due to its ability to extract spatial features from images.
Results Summary
Model	Training Accuracy	Validation Accuracy	Notes
ANN	~98%	~97.6%	Good baseline performance
CNN	~99.4%	~99.0%	Best performance; no overfitting
Both models show stable training behavior and do not exhibit overfitting, thanks to proper normalization and early stopping.
