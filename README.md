Hand Gesture Recognition System

A deep learning based Hand Gesture Recognition system built using Convolutional Neural Networks (CNN) and the LeapGestRecog dataset.
The system classifies hand gestures and enables intuitive human–computer interaction.

Overview

This project implements an image classification model capable of recognizing 10 different hand gestures from infrared images.
It also supports webcam-based gesture prediction for real-time interaction.

The project was developed as part of an AI/ML internship task.

Dataset

Dataset used: LeapGestRecog
Source: Kaggle
Total Images: 20,000+
Classes: 10 hand gestures

Each class represents a unique gesture captured using a Leap Motion sensor.

Technologies Used

Python

TensorFlow / Keras

OpenCV

NumPy

Matplotlib

Scikit-learn

Model Architecture

The model is built using a Convolutional Neural Network with:

Data Augmentation

Rescaling Layer

3 Convolutional Layers

MaxPooling Layers

Dropout Regularization

Fully Connected Dense Layers

Softmax Output Layer (10 Classes)

Training Details

Image Size: 128x128

Batch Size: 32

Optimizer: Adam

Loss Function: Sparse Categorical Crossentropy

Epochs: 15

Performance

Training Accuracy: ~95%

Validation Accuracy: ~92–95%

Model evaluation includes:

Confusion Matrix

Classification Report

Precision, Recall, F1-Score

Features

Static image gesture classification

Real-time webcam gesture detection

Performance visualization

Model saving and loading support

Project Structure
Hand-Gesture-Recognition/
│
├── dataset/
├── gesture_model.h5
├── training_notebook.ipynb
├── webcam_detection.py
└── README.md

How to Run

Clone the repository

Install required dependencies:

pip install tensorflow opencv-python numpy matplotlib scikit-learn


Train the model or load the saved model

Run webcam_detection.py for real-time prediction

Future Improvements

Transfer Learning using MobileNetV2

LSTM for dynamic gesture recognition

Web deployment using Streamlit

Mobile application integration

Author

Amogh Waskar
Artificial Intelligence & Machine Learning Enthusiast
