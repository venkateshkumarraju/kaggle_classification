
# opencv-pytorch-classification

## Introduction
The project is aimed at building an image classification model using PyTorch. It includes several stages, such as data loading, model configuration, training, validation, and evaluation. The primary goal is to achieve high classification accuracy on a dataset (possibly KenyanFood13 or another) by implementing and tuning a Convolutional Neural Network (CNN).

# Dataset
Load the dataset using a custom dataset class in PyTorch, and split the training data into train and validation sets (usually 80:20).

# Model Architecture
The model likely follows a Convolutional Neural Network (CNN) architecture with layers such as:

Convolutional layers for feature extraction
Pooling layers for down-sampling
Fully connected layers for classification
Output layer with softmax activation for multi-class classification
