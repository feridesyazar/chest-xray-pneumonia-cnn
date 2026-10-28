# 🫁 Chest X-Ray Pneumonia Classification with CNN

### Deep Learning | Binary Image Classification

Can a Convolutional Neural Network (CNN) distinguish between NORMAL and PNEUMONIA chest X-ray images?

This project uses TensorFlow and Keras to build a simple CNN, train it on chest X-ray images, and evaluate its classification performance.

## Project Overview

- **Dataset:** Chest X-Ray Images (Pneumonia)
- **Problem Type:** Supervised Learning | Binary Classification
- **Model:** Convolutional Neural Network (CNN)
- **Tools:** Python, TensorFlow, Keras, NumPy, Matplotlib, Scikit-learn

## Workflow

- Load and explore chest X-ray images
- Build and train a CNN model
- Visualize training and validation accuracy
- Evaluate test performance
- Analyze the Classification Report and Confusion Matrix

## Results

- **Training Accuracy:** Approximately 97%
- **Test Accuracy:** 70.99%
- **PNEUMONIA Recall:** 99.74%
- **NORMAL Recall:** 23.08%

## Conclusion

The model identified most PNEUMONIA images correctly but struggled with NORMAL images.

Class imbalance, a small validation set, and possible overfitting highlight the importance of **generalization** and balanced model performance.

This project is for educational purposes only and is not suitable for medical diagnosis.

## Dataset

[Chest X-Ray Images (Pneumonia) — Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
