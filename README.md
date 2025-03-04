# Classification of medical images with convolutional networks
This repository contains a deep learning solution for **medical image classification** using **Convolutional Neural Networks (CNNs)**. The goal is to accurately identify different **pathologies and tissue types** from medical images.

## 📌 Project Overview

Medical image classification is a crucial task in **computer-aided diagnosis (CAD)**, assisting healthcare professionals in detecting and diagnosing diseases. This project utilizes CNN-based models to classify images from the **MedMNIST dataset**, a diverse collection of medical imaging modalities.

For more details on the dataset, visit: [MedMNIST](https://medmnist.com/).

## 🚀 Approach

### 1️⃣ Data Preparation
- Download and preprocess the **MedMNIST dataset**  
- Normalize pixel values and apply data augmentation  
- Split dataset into **training, validation, and test sets**  

### 2️⃣ Model Development
- Implement **Convolutional Neural Networks (CNNs)** using PyTorch  
- Experiment with different architectures (e.g., **ResNet, EfficientNet, VGG16**)  
- Fine-tune **hyperparameters** and optimize performance  

### 3️⃣ Training & Evaluation
- Train the model with **cross-entropy loss** and **Adam optimizer**  
- Evaluate using metrics like **accuracy, F1-score, AUC-ROC**  
- Implement **Grad-CAM** for explainability  

### 4️⃣ Deployment & Inference
- Deploy trained models for real-time classification  
- Test on unseen medical images  
- Package results for visualization and analysis  

## 📊 Dataset

The **MedMNIST dataset** consists of multiple medical imaging modalities, including:
- **OrganMNIST** (Abdominal CT scans)  
- **PathMNIST** (Histopathology images)  
- **ChestMNIST** (Chest X-rays)  
- **DermaMNIST** (Skin lesion images)  
- **OCTMNIST** (Retinal OCT scans)  

Each dataset contains labeled images for supervised learning.
