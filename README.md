# 🐦 Bird Species Classification using Machine Learning and Deep Learning

## 📌 Project Overview

This project focuses on classifying bird species using various Machine Learning (ML) and Deep Learning (DL) techniques. It aims to categorize images of 25 different bird species found in India using both traditional feature-based models and modern Convolutional Neural Networks (CNNs).

---

## 🗂 Dataset

- **Total Images**: 37,500 (1,500 images per class × 25 classes)
- **Original Split**: 1,200 train / 300 validation per class  
- **Adjusted Split**:  
  - 80% Training (1,200)  
  - 10% Validation (150)  
  - 10% Test (150)  
- **Image Size**: ~1 Megapixel  
- You may use downscaled images or a subset of the dataset if hardware limitations apply, but **preserve the 80-10-10 ratio** and avoid excessive downsampling.

---

## 🧭 Project Structure

### 🔹 Part 1: Feature Extraction & Traditional ML

- **Extracted Features**:
  - Color
  - Color Histogram
  - SIFT, HoG, Gabor Filters

- **Machine Learning Models**:
  - Support Vector Machines (SVM)
  - Random Forest
  - Naive Bayes
  - Multilayer Perceptron (MLP)

---

### 🔹 Part 2: Dimensionality Reduction & Feature Selection

- **Techniques Used**:
  - Principal Component Analysis (PCA)
  - A feature selection method that eliminates features 

- **Evaluation**:
  - Applied ML models from Part 1 on PCA-reduced and selected features
  - Compared with raw feature performance

---

### 🔹 Part 3: Fine-Tuning Pretrained CNNs

- **Selected Models**: 3 pretrained CNNs 
- **Methodology**:
  - Fine-tune models on the dataset
  - Plot and analyze training/validation loss and accuracy
  - Use early stopping based on loss graphs

---

### 🔹 Part 4: Training CNNs from Scratch (Random Weights)

- **Method**:
  - Same CNN architectures from Part 3, but initialized with random weights
  - Trained from scratch on the same dataset
  - Compared with fine-tuned versions
  - Provided similar plots and commentary

---

### 🔹 Part 5: Custom CNN Architecture

- **Objective**:
  - Design and train a custom CNN model
  - Tune layers, activation functions, optimizers, etc.

- **Process**:
  - Conducted multiple trials
  - Tracked performance and design decisions
  - Compared with pretrained and random CNNs


