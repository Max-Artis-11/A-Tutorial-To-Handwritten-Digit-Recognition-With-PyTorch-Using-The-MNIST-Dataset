# PyTorch CNN Tutorial: Handwritten Digit Recognition Using The MNIST Dataset

This project demonstrates how to build, train, and evaluate a Convolutional Neural Network (CNN) using **PyTorch**. The model is trained to classify handwritten digits from the **MNIST** dataset, which contains images of digits from 0 to 9. By the end of this project, you'll be able to understand the basics of building and training deep learning models using PyTorch, and how CNNs are used for image classification tasks.

---

## Features

- **PyTorch** framework to implement a CNN model.
- **CNN Architecture** with 2 convolutional layers followed by fully connected layers.
- **Training loop** to optimize model parameters.
- **Testing & evaluation** on the MNIST dataset to check accuracy.
- **Visualization** of predictions using **matplotlib**.
- Optimized using **Adam** optimizer and **CrossEntropyLoss** for multi-class classification.

---

## Project Overview

### Dataset: MNIST
The **MNIST** dataset is a collection of 60,000 28x28 grayscale images of handwritten digits (0-9) used for training, and 10,000 images used for testing. Each image is labeled with the corresponding digit. The dataset is commonly used for training image classification models.

### Model: Convolutional Neural Network (CNN)
A Convolutional Neural Network (CNN) is a type of deep neural network that excels in processing and classifying image data. It works by applying filters (or kernels) to images to detect patterns and features such as edges, textures, or shapes. The CNN model in this project includes:

- **Conv2d Layers**: To extract features from the images.
- **ReLU Activations**: To introduce non-linearity and help the network learn complex patterns.
- **MaxPool2d**: To down-sample the images and reduce the computational complexity.
- **Fully Connected Layers**: To classify the extracted features into 10 classes (digits 0-9).
- **Dropout**: To prevent overfitting by randomly dropping connections during training.

---

## Installation

### 1. Clone the repository:

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
