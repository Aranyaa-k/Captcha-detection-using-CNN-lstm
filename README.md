# CAPTCHA Recognition System with CNN and LSTM

Overview
This project aims to enhance Optical Character Recognition (OCR) in CAPTCHA images by leveraging Convolutional Neural Networks (CNNs) and Bidirectional Long Short-Term Memory (LSTM) layers. The objective is to accurately interpret alphanumeric characters and improve CAPTCHA security against automated script intrusions.

# Abstract
The project begins with curated CAPTCHA image datasets, undergoing meticulous preprocessing, including grayscale conversion, pixel normalization, and character extraction. Two neural network architectures are developed - one using CNNs exclusively and the other integrating Bidirectional LSTM layers post-CNN. The system is designed to recognize complex patterns and sequences within CAPTCHA images, contributing to the advancement of OCR systems for CAPTCHAs.

# Getting Started
# Prerequisites
Python (>=3.6)
Keras
TensorFlow

# Methodology
The algorithm involves importing necessary libraries, decoding text into indices, splitting datasets, and creating a neural network with CNN and LSTM layers. The project utilizes a dataset of 1070 standard noise dataset from Kaggle, 10,000 images generated using the Python Image Captcha Library, and 10,000 randomly selected fisheye CAPTCHAs. The high-level neural network library Keras is utilized for implementation.

#Model Architecture
•Convolutional Neural Network (CNN):

Designed for processing structured grid data, such as images.
Consists of convolutional layers for detecting spatial patterns, pooling layers for downsampling, and ReLU activation functions for introducing non-linearity.
Leverages shared weights to capture hierarchical representations.
Bidirectional LSTM:

Consists of three gates for selectively retaining and discarding information.
Overcomes the vanishing gradient problem experienced by recurrent neural networks (RNNs).

The CNN+LSTM model was tested on 3 different datasets
- Fisheye dataset of 10,000 images
- Custom captcha dataset of 10,000 images
- Standard captcha dataset of 10,000 images

The details of the model and the results can be seen in the ipynb files above

