# MNIST Digit Classification using Neural Network

## Overview

This project implements a Neural Network for handwritten digit classification using the MNIST dataset.

The model is built using TensorFlow/Keras and achieves approximately **97.43% test accuracy**.

## Dataset

MNIST Dataset

* 70,000 grayscale handwritten digit images
* 28 × 28 pixel resolution
* 10 output classes (digits 0–9)

Dataset Split:

* Training Images: 60,000
* Testing Images: 10,000

## Project Workflow

1. Dataset Upload and Extraction
2. Data Loading using IDX Files
3. Data Visualization
4. Pixel Value Normalization
5. Neural Network Construction
6. Model Training
7. Model Evaluation
8. Accuracy and Loss Visualization
9. Confusion Matrix Generation
10. Sample Predictions

## Neural Network Architecture

Input Layer:

* Flatten (28×28 → 784)

Hidden Layers:

* Dense(128, ReLU)
* Dense(64, ReLU)

Output Layer:

* Dense(10, Softmax)

## Results

| Metric        | Value  |
| ------------- | ------ |
| Test Accuracy | 97.43% |
| Test Loss     | 0.105  |

## Visualizations

* Sample Digit Visualization
* Accuracy Curve
* Loss Curve
* Confusion Matrix
* Sample Prediction

## Technologies Used

* Python
* NumPy
* TensorFlow
* Keras
* Matplotlib
* Seaborn
* Scikit-Learn

## Learning Outcomes

* Neural Network Fundamentals
* Image Classification
* Data Preprocessing
* Model Evaluation
* Visualization of Training Performance

## Author

Panav Gohil
