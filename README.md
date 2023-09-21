# CIFAR-10 Image Classification with Multi-Layer Perceptron (MLP)

## Overview

This repository contains a simple implementation of an image classification task using a Multi-Layer Perceptron (MLP) for the CIFAR-10 dataset. CIFAR-10 is a dataset consisting of 60,000 32x32 color images divided into 10 classes, including airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. Each image is composed of three color channels (Red, Green, and Blue), resulting in a total of 3x32x32 = 3072 pixels. The dataset is further split into 50,000 training images and 10,000 test images.

## Model Description

- The MLP model architecture comprises two hidden layers with Rectified Linear Unit (ReLU) activations.
- The first hidden layer consists of 256 nodes, while the second hidden layer has 128 nodes.
- To prevent overfitting, dropout layers with a 30% dropout rate are applied after each hidden layer.
- An L2 regularizer with a coefficient of λ = 0.0001 is employed to mitigate overfitting.

## Confusion Matrix Usage

(a) For each object type (e.g., airplane, car, bird, etc.), the confusion matrix will reveal the class that is most likely to be confused with that object type.

(b) The confusion matrix will also help identify which two classes (object types) are most likely to be confused over, providing valuable information about the model's strengths and weaknesses in distinguishing between different objects.
