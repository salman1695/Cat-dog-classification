# 🐱🐶 Cat vs Dog Image Classification – Android + Deep Learning

This project demonstrates a deep learning model that classifies images as **Cat** or **Dog**, trained using TensorFlow/Keras and deployed in a real-time Android application using Android Studio.

## 🎯 Features

- 🧠 Image classification model trained on cat and dog images
- ✅ Model converted and optimized for mobile using TensorFlow Lite
- 📱 Real-time prediction in Android Studio using Camera or Gallery image
- ⚡ Fast and lightweight inference

## 🧪 Training Details

- Language: Python
- Libraries: TensorFlow / Keras
- Model File: `Model1.keras`
- Test Script: `Test_model_for_one_img.ipynb`

## 📦 Files Included

- `cat_dog_classification.ipynb` – Training notebook for the deep learning model
- `Test_model_for_one_img.ipynb` – Testing notebook for single image prediction
- `Model1.keras` – Trained model file
  

## 📲 Android Integration

- TensorFlow Lite model used for mobile inference
- Android app built in **Android Studio**
- Features:
  - Image picker from gallery/camera
  - Predicts cat or dog with probability score

## 🛠️ Requirements

### For Model Training:
```bash
pip install tensorflow opencv-python matplotlib
