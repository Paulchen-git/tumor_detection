# Brain Tumor Detection using Neural Networks

This project focuses on the classification of brain MRI images to detect tumors using two types of neural networks: Multi-Layer Perceptron (MLP) and Convolutional Neural Network (CNN).

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
    - [Multi-Layer Perceptron (MLP)](#multi-layer-perceptron-mlp)
    - [Convolutional Neural Network (CNN)](#convolutional-neural-network-cnn)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction
Brain tumor detection is a critical task in medical imaging. This project aims to classify brain MRI images to detect the presence of tumors using two different neural network architectures: MLP and CNN.

## Dataset
The dataset used in this project consists of brain MRI images labeled as either having a tumor or not. The images are preprocessed and split into training and testing sets.

## Models

### Multi-Layer Perceptron (MLP)
The MLP model is a fully connected neural network that consists of multiple layers of neurons. It is trained on the flattened MRI images to classify them as tumor or non-tumor.

### Convolutional Neural Network (CNN)
The CNN model is a deep learning architecture specifically designed for image classification tasks. It consists of convolutional layers, pooling layers, and fully connected layers. The CNN model is trained on the MRI images to detect tumors with higher accuracy.

## Results
The performance of both models is evaluated using metrics such as accuracy, precision, recall, and F1-score. The results show that the CNN model outperforms the MLP model in terms of accuracy and other evaluation metrics.

## Usage
To run the notebook and train the models, follow these steps:
1. Clone the repository.
2. Install the required dependencies.
3. Run the notebook to preprocess the data, train the models, and evaluate their performance.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.
