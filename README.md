# MNIST Digit Classification with CNN

Deep learning project for handwritten digit classification on the MNIST dataset using TensorFlow/Keras.

## Overview

This project builds and trains a Convolutional Neural Network (CNN) to classify handwritten digits from 0 to 9.

The workflow includes:

- Data loading and preprocessing
- Train/validation/test split
- Image normalization and reshaping
- One-hot encoding of target labels
- CNN model development
- Training with early stopping
- Model evaluation
- Confusion matrix analysis

## Technologies

- Python
- TensorFlow / Keras
- NumPy
- scikit-learn
- Matplotlib

## Model Architecture

The CNN uses:

- Conv2D layers
- MaxPooling2D layers
- Dropout
- Dense layers
- Softmax output layer

The model is trained using the Adam optimizer and categorical cross-entropy loss.

## Results

The model achieved approximately **98.6% accuracy on the test set**.

A confusion matrix is also used to inspect classification performance across the ten digit classes.

## Files

- `mnist_cnn_classification.ipynb` – complete preprocessing, model training and evaluation

The MNIST dataset is loaded directly through TensorFlow/Keras and does not need to be stored separately in the repository.

## Purpose

This project was developed as part of my MSc in Data Science and Machine Learning and demonstrates hands-on experience with convolutional neural networks, image classification and deep learning workflows.
