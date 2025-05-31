# Diabetes Classification with a Neural Network

This project implements a simple neural network (MLP) in Python using NumPy to predict diabetes using the Pima Indians Diabetes dataset.

## Objective

The goal is to predict whether a patient has diabetes based on medical features. The model is built and trained **from scratch**, without using deep learning libraries like TensorFlow or PyTorch.

## Project Files

- `neural_network.py` – MLP model with Adam optimizer  
- `train.py` – Code to load data, train, and evaluate the model  
- `diabetes.csv` – Dataset used for training and testing  
- `README.md` – This file

## Features

- Manual implementation of:
  - Forward and backward propagation
  - ReLU and Sigmoid activations
  - Adam optimizer
  - L2 regularization
- Accuracy, F1-score, confusion matrix
- Training and validation curves

