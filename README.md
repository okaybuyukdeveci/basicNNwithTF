# Insurance Charge Prediction with Neural Networks

This repository contains a Python project for predicting insurance charges based on a variety of factors using a neural network. The dataset used is publicly available and includes attributes such as age, sex, BMI, number of children, smoking status, and region. The goal is to understand how these factors influence insurance costs and to build a model that can accurately predict charges.

DATA = https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/refs/heads/master/insurance.csv

# Model Architecture
The project implements several neural network models with TensorFlow, including:

Baseline Model: A simple model with one hidden layer.
Model 2: A more complex model with additional layers and neurons.
Model 3: A model that further increases complexity with more training epochs.
Normalized Model: A model that uses Min-Max scaling and one-hot encoding for preprocessing.
The models are trained to minimize the Mean Absolute Error (MAE) metric.

# Results
The project evaluates each model on a test set and plots the loss over epochs. The evaluation results indicate the performance of each model, with the normalized model typically performing better due to improved feature scaling.
