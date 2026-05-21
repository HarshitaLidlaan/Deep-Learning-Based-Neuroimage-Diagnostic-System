# Deep-Learning-Based-Neuroimage-Diagnostic-System
Deep learning-based brain CT scan classification system with Multi class disease detection, Explainable AI and OOD detection using ResNet18.

# Overview
This project is an AI-powered neuroimage diagnostic system developed for automated brain CT scan classification using deep learning techniques. The system utilizes a pretrained ResNet18 Convolutional Neural Network (CNN) model to classify neuroimages into Hemorrhage, Ischemia, and Normal categories.

The project integrates Explainable AI (XAI) using Grad-CAM++ heatmaps to improve prediction interpretability and transparency. It also includes Out-of-Distribution (OOD) Detection using Mahalanobis Distance to identify unreliable or unseen inputs and improve model reliability.

A Streamlit-based web application is implemented for real-time CT scan upload, prediction visualization, confidence scoring, and diagnostic assistance.

## Features

- Brain CT scan classification using ResNet18 CNN
- Multi-class prediction: Hemorrhage, Ischemia, Normal
- Explainable AI visualization using Grad-CAM++
- OOD Detection for unreliable input identification
- Real-time prediction through Streamlit web interface
- Prediction confidence scoring and heatmap visualization

## Tech Stack

- Python
- PyTorch
- TensorFlow
- ResNet18 CNN
- Streamlit
- NumPy
- Matplotlib
- PIL

## Future Scope

- Multi-modal medical imaging integration using CT and MRI datasets
- Advanced stroke subtype classification
- Federated learning for secure medical data privacy
- Improved real-world clinical validation and deployment
