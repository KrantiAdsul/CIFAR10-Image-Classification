# CIFAR10-Image-Classification

This repository contains a simple implementation of an image classification task using a Multi-Layer Perceptron (MLP) for the CIFAR-10 dataset. CIFAR-10 is a dataset consisting of 60,000 32x32 color images in 10 classes, including airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. Each image has three color channels (Red, Green, and Blue), resulting in a total of 3x32x32 = 3072 pixels. The dataset is split into 50,000 training images and 10,000 test images.

Description
The MLP model architecture consists of two hidden layers with ReLU activations.
The first hidden layer has 256 nodes, and the second hidden layer has 128 nodes.
Dropout layers with a 30% dropout rate are applied after each hidden layer to prevent overfitting.
An L2 regularizer with a coefficient of λ = 0.0001 is used to control overfitting.

(a) For each object type (e.g., airplane, car, bird, etc.), the confusion matrix will reveal the class that is most likely to be confused with that object type.

(b) The confusion matrix will also help identify which two classes (object types) are most likely to be confused over, providing valuable information about the model's strengths and weaknesses in distinguishing between different objects.
