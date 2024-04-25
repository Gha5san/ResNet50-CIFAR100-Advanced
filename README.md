# CIFAR-100 ResNet50 Object Classifcation

## Overview
This repository contains the implementation of an enhanced ResNet50 model aimed at improving image classification on the CIFAR-100 dataset. It explores advanced hyperparameters, data augmentation techniques, and incorporates a custom attention mechanism to boost performance.

## Model Details
- **Base Model**: ResNet50, pre-trained on ImageNet.
- **Modifications**: Integration of a squeeze-excite block for better feature representation.
- **Hyperparameters**: Optimization via Optuna for learning rate and dropout rate settings.

## Results
- **Accuracy**: 58.13%
- **Precision**: 68.54%
- **Recall**: 52.96%
- **F1 Score**: 59.75%

## Dataset
The CIFAR-100 dataset consists of 60,000 32x32 color images across 100 classes, making it a challenging dataset for deep learning models.
