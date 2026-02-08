# Deep Learning Project: Pre-trained Models on Vision Datasets

This project is part of a deep learning assignment where multiple **pre-trained models** from `torchvision.models` are trained and evaluated on a vision dataset. The goal is to compare model performance in terms of **test accuracy**.

---

## Project Overview

**Objective:**  
Train and evaluate pre-trained models on image classification datasets using PyTorch, modifying the final layer to match the number of classes in the chosen dataset.

**Datasets Used:**  
- MNIST (subset of 5000 training images and 1000 test images)  

**Pre-trained Models Evaluated:**  
- ResNet18  
- VGG16  
- MobileNetV2  

## Results

The following table summarizes the **test accuracy** of each trained pre-trained model on the MNIST dataset:

| Model        | Test Accuracy (%) |
|-------------|-----------------|
| ResNet18    | 97.90           |
| VGG16       | 91.50           |
| MobileNetV2 | 98.00           |


**Key Features:**  
- Utilizes GPU if available for faster training.  
- Implements data transformations including resizing to 224x224 and normalization.  
- Training with **Adam optimizer**, **CrossEntropyLoss**, **batch size 32**, and **learning rate 0.001**.  
- 5 epochs per model.  

---

## 🛠 Installation & Setup

1. Clone the repository:
   ```bash
   git clone <your-repo-link>
   cd <repo-folder>
