# Hand Gesture Recognition System

A deep learning-based computer vision system that recognizes and classifies hand gestures using Convolutional Neural Networks (CNN).  
This project demonstrates the practical implementation of image classification for gesture-based human–computer interaction.

---

## Project Objective

To develop a robust gesture recognition model capable of accurately identifying hand gestures from image data and enabling real-time gesture-based control systems.

The system bridges computer vision with interactive AI applications.

---

## Dataset

**Dataset:** LeapGestRecog  
**Source:** Kaggle  
**Total Images:** 20,000+  
**Classes:** 10 hand gestures  
**Data Type:** Infrared grayscale images captured using a Leap Motion sensor  

Each class represents a distinct static hand gesture.

---

## Technical Stack

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## Methodology

### 1. Data Preprocessing
- Image resizing to 128 × 128  
- Pixel normalization (Rescaling 1/255)  
- Data augmentation (horizontal flip, rotation, zoom)  
- Training–validation split (80–20)

### 2. Model Architecture

The CNN architecture consists of:

- Data Augmentation Layer  
- Rescaling Layer  
- 3 Convolutional Layers (ReLU activation)  
- MaxPooling Layers  
- Dropout Regularization  
- Fully Connected Dense Layer  
- Softmax Output Layer (10 classes)

This architecture enables hierarchical feature extraction from gesture images.

### 3. Model Training

- Optimizer: Adam  
- Loss Function: Sparse Categorical Crossentropy  
- Batch Size: 32  
- Epochs: 15  
- Validation Monitoring  

---

## Performance Metrics

- Training Accuracy: ~95%  
- Validation Accuracy: ~92–95%  

Evaluation methods include:

- Confusion Matrix  
- Classification Report  
- Precision  
- Recall  
- F1-Score  

The model demonstrates strong generalization across gesture classes.

---

## Real-Time Gesture Detection

The trained model supports webcam-based gesture prediction using OpenCV.

### Workflow:
1. Capture frame from webcam  
2. Resize and normalize image  
3. Perform model inference  
4. Display predicted gesture label  

This enables real-time interactive applications.

---

## Key Features

- End-to-end deep learning pipeline  
- Data augmentation for improved generalization  
- Detailed model evaluation  
- Real-time prediction capability  
- Clean and modular code structure  

---

## Potential Applications

- Touchless control systems  
- Virtual reality interaction  
- Smart home automation  
- Assistive technologies  
- Robotics and automation  

---

## Future Enhancements

- Transfer Learning (MobileNetV2 / ResNet)  
- LSTM-based dynamic gesture recognition  
- Deployment using Streamlit or Flask  
- Edge-device optimization  
- Integration with IoT systems  

---

## Learning Outcomes

This project strengthened practical understanding of:

- Convolutional Neural Networks  
- Image preprocessing techniques  
- Model evaluation strategies  
- Real-time inference pipelines  
- Applied computer vision systems  

---

## Author

**Amogh Waskar**  
Artificial Intelligence & Machine Learning Enthusiast  
Focused on building intelligent systems that merge vision and interaction.



