# CIFAR-10 Image Classification using CNN (PyTorch)

## Overview
This project implements an image classification model using a Convolutional Neural Network (CNN) built with PyTorch. The model is trained on the CIFAR-10 dataset to classify images into 10 different object categories.

The project demonstrates the application of deep learning techniques for computer vision tasks including data preprocessing, model training, evaluation, and visualization of training performance.

## Dataset
The project uses the CIFAR-10 dataset provided by Torchvision.

Dataset Characteristics:
- 60,000 images
- 10 classes
- Image size: 32x32 RGB
- 50,000 training images
- 10,000 test images

Classes include:
Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck

## Technologies Used

- Python
- PyTorch
- Torchvision
- Matplotlib
- Pandas
- Deep Learning (CNN)

## Project Workflow

1. Import required libraries
2. Load CIFAR-10 dataset
3. Apply image preprocessing and normalization
4. Create DataLoader for batch training
5. Build a Convolutional Neural Network
6. Train the model using Adam optimizer
7. Evaluate model performance on test dataset
8. Visualize training and validation loss

## CNN Architecture

The model includes:

- Convolutional Layers
- ReLU Activation
- MaxPooling Layers
- Fully Connected Layer
- Softmax classification

## Model Training

- Loss Function: CrossEntropyLoss
- Optimizer: Adam
- Epochs: 10
- Batch Size: 64

## Results

The model successfully learns image representations and classifies CIFAR-10 images with reasonable accuracy.

Training and validation loss curves are visualized to monitor learning progress.
