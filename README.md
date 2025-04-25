# PURVA BAGHEL  
**PRN:** 22070521130  
**Semester:** 6 

---

## 📚 Case Study Report: Continuous Assessment of Introduction to Deep Learning

This case study presents two deep learning projects developed as part of the continuous internal assessment for the course "Introduction to Deep Learning." The first project focuses on using Generative Adversarial Networks (GANs) for generating clarified chest X-ray images, while the second revolves around building a robust traffic sign classifier using Convolutional Neural Networks (CNNs). Both projects demonstrate the practical application of deep learning techniques to solve real-world problems, integrating concepts such as data preprocessing, model training, image classification, and performance evaluation.

---

## 🧠 Project 1: Chest X-ray Image Generation using GAN

### 🔍 Introduction
Medical image enhancement and synthetic image generation have seen remarkable advancements with the advent of deep learning. This project leverages Generative Adversarial Networks (GANs) to generate clarified and realistic chest X-ray images, which can aid in early detection of diseases like pneumonia. The model is trained to understand the structure and texture of X-ray images and then reproduce synthetic samples that closely resemble the real ones.

### ❗ Problem Statement
Chest X-rays are a primary diagnostic tool for pulmonary diseases. However, low-quality or noisy X-ray images may hinder proper diagnosis. There is a need for enhanced and high-quality medical imaging to support accurate detection, particularly in cases where labeled datasets are limited.

### 💡 Need for the Solution
- To assist radiologists by generating clarified versions of X-rays for better interpretation.
- To augment the medical imaging dataset using synthetic images, especially in data-scarce environments.
- To explore and apply GANs for medical image synthesis and enhancement tasks.

### 🚀 Project Highlights
- Implemented a basic GAN architecture comprising a Generator and a Discriminator.
- Trained the model on chest X-ray images (with and without pneumonia).
- Generated synthetic X-rays that resemble the real medical images.
- Visualized training progress and compared original vs generated images.
- Potential use-case: Data augmentation for pneumonia classification tasks.

---

## 🚦 Project 2: Traffic Sign Classification

### 🔍 Introduction
Accurate recognition of traffic signs is essential for autonomous vehicles and modern driver-assistance systems. This project implements a deep learning model using CNNs to classify traffic signs from images. The classifier helps vehicles understand road rules by identifying signs such as speed limits, warnings, and prohibitions.

### ❗ Problem Statement
Traffic signs come in various shapes, colors, and languages, and recognizing them under different environmental conditions (blur, lighting, angle) is a challenging task. Traditional image processing techniques are not robust enough to handle the variability.

### 💡 Need for the Solution
- To build a reliable and automated system capable of recognizing road signs in real-time.
- To contribute to the development of intelligent transportation systems and self-driving vehicles.
- To enhance road safety by minimizing human error in sign interpretation.

### 🚀 Project Highlights
- Utilized a CNN-based architecture for multi-class classification of traffic signs.
- Dataset preprocessing included image resizing, normalization, and label encoding.
- Achieved high classification accuracy across various sign categories.
- Evaluated model performance using confusion matrices and accuracy metrics.
- Visualized predictions to validate real-world application effectiveness.

---

## ⚙️ Installation and Setup

To run both projects, follow the steps below:

### ✅ Prerequisites
Ensure you have **Python 3.7+** installed. You can use `pip` or `conda`.

### 📦 Recommended Libraries

Create a virtual environment:
```bash
python -m venv dl_env
source dl_env/bin/activate   # On Windows use: dl_env\Scripts\activate
