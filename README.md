# Handwritten Image Classification using Deep Learning

This repository contains a Python notebook that demonstrates how to build a neural network for classifying handwritten digits using the MNIST dataset. The notebook uses TensorFlow and Keras libraries to construct and train the neural network.

## Dataset

The MNIST dataset is a large database of handwritten digits that is commonly used for training various image processing systems. It includes 60,000 training images and 10,000 testing images of handwritten digits.

## Model Architecture

The neural network model used in this project consists of the following layers:
- Flatten layer to convert each 28x28 image into a 784-dimensional vector.
- Dense layer with 128 units and ReLU activation.
- Dense layer with 64 units and ReLU activation.
- Dense layer with 10 units and softmax activation for classification.

## Requirements

- TensorFlow
- Keras
- Matplotlib

You can install the required libraries using pip:

```bash
pip install tensorflow matplotlib
