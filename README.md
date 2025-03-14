# PyTorch ANN for MNIST Digit Classification

## Description

This project implements an **Artificial Neural Network (ANN)** using **PyTorch** to classify handwritten digits from the **MNIST dataset**. The model is trained to recognize digits (0-9) with high accuracy.

## Features

- **ANN-based digit classification**
- **Trained on MNIST dataset**
- **Utilizes PyTorch for deep learning**
- **Batch normalization and ReLU activation**
- **Optimized with Adam optimizer & CrossEntropy Loss**

## Technologies Used

- **PyTorch**
- **Torchvision**
- **Matplotlib**
- **Python**

## Installation

Install the required dependencies:

```bash
pip install torch torchvision matplotlib numpy
```

## Dataset

The project uses the **MNIST dataset**, which contains **60,000 training images** and **10,000 test images** of handwritten digits, each of size **28x28 pixels**.

## Training

- **Loss Function:** CrossEntropyLoss
- **Optimizer:** Adam (lr=0.001)
- **Batch Size:** 10
- **Epochs:** 10

## Results

- Train accuracy and loss
- Test accuracy
- Predictions at the end

## Future Improvements

- Experiment with **deeper networks (more layers)**
- Implement **Convolutional Neural Networks (CNNs)**
- Use **data augmentation** for better generalization

