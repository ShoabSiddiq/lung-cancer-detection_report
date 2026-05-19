# Lung Cancer Detection using Deep Learning

## 📌 Overview
This project presents a deep learning-based approach for detecting and classifying lung cancer using histopathological images. The goal is to classify lung tissue into three categories:
- Lung Adenocarcinoma
- Lung Squamous Cell Carcinoma
- Benign Lung Tissue

## 📊 Dataset
The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images

- Total images used: 15,000
- Classes: 3
- Image size: 768×768 pixels

## 🔍 Methodology
The project uses transfer learning with several pre-trained convolutional neural network models:

- VGG16
- VGG19
- ResNet50
- InceptionV3
- MobileNetV2

Steps:
1. Data preprocessing and augmentation
2. Model training using transfer learning
3. Evaluation using accuracy, precision, recall and F1-score

## 📈 Results
The performance of each model is as follows:

- VGG16: 96.76%
- VGG19: 94.90%
- ResNet50: 74.43%
- InceptionV3: 95.76%
- MobileNetV2: **97.83% (Best Model)**

MobileNetV2 achieved the highest performance, showing strong potential for medical image classification.

## 🧠 Tools & Technologies
- Python
- TensorFlow / Keras
- NumPy / Pandas
- Matplotlib / Seaborn
- Google Colab

## ▶️ How to Run
1. Open the notebook in Jupyter or Google Colab
2. Install required libraries
3. Run all cells step-by-step
