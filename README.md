# CIFAR-10 Image Classification using CNN

## 📌 Overview
A simple **Convolutional Neural Network (CNN)** built with **PyTorch** to classify images from the **CIFAR-10 dataset**.

Dataset:
- 60,000 color images (50,000 training / 10,000 testing)
- Image size: 32×32 pixels
- 10 classes: Plane, Car, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck

## 🛠️ Technologies
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib

## 🧠 Model Architecture
The CNN model includes:
- Convolutional layers
- ReLU activation
- Max Pooling layers
- Fully Connected layers
- Output layer with 10 classes

Training configuration:
- Optimizer: Adam
- Loss Function: Cross Entropy Loss
- Batch Size: 64
- Epochs: 5

## 📊 Results
The model is evaluated on the CIFAR-10 test dataset and provides:
- Test Accuracy
- Prediction results compared with ground truth labels
- Visualization of image predictions

The trained model weights are saved as:
cifar10_cnn.pth
