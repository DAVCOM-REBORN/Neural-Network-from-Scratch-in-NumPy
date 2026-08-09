PROJECT DESCRIPTION
===================

Project: Neural Network From Scratch with NumPy

This project implements a fully connected neural network from scratch using
NumPy for handwritten digit classification on the MNIST dataset.

The network receives 28x28 grayscale images, flattens each image into 784
features, passes the data through a hidden layer containing 128 neurons with
ReLU activation, and produces 10 class probabilities using softmax.

The implementation covers data preprocessing, one-hot encoding, He
initialization, forward propagation, cross-entropy loss, backpropagation and
full-batch gradient descent.

TensorFlow is used to load the MNIST dataset, while NumPy performs the neural
network calculations.

The supplied notebook reported 97.8% training accuracy at epoch 400 and
94.48% test accuracy in its executed evaluation.

Main learning objectives:
- Understand neural-network architecture.
- Understand matrix dimensions through forward propagation.
- Implement activation functions manually.
- Understand and implement backpropagation.
- Understand gradient descent and parameter updates.
- Evaluate a classification model on unseen test data.

The project is educational and is intended to demonstrate the internal
mechanics of a basic neural network rather than provide a production-ready
MNIST classifier.
