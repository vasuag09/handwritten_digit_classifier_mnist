# 🧠 Handwritten Digit Classifier (MNIST) using Artificial Neural Network (ANN)

This project implements a neural network model to classify handwritten digits (0–9) from the MNIST dataset using TensorFlow and Keras.

![Digit Samples](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

---

## 📌 Project Overview

- **Dataset**: [MNIST Handwritten Digits](http://yann.lecun.com/exdb/mnist/)
- **Model Type**: Artificial Neural Network (ANN)
- **Frameworks**: TensorFlow, Keras, NumPy, Matplotlib, Seaborn
- **Goal**: Achieve high classification accuracy on handwritten digits (0–9)

## 🧪 Features

- Clean preprocessing: normalization + one-hot encoding
- Fully connected ANN with:
  - Input layer (784 nodes)
  - Two hidden layers (64 & 32 units)
  - Output layer with 10 softmax nodes
- Dropout & EarlyStopping to reduce overfitting
- Accuracy: **~98% on validation set**
- Confusion matrix and classification report for performance insight

---

## 📊 Sample Results

| Metric         | Value   |
|----------------|---------|
| Train Accuracy | 98.00%  |
| Val Accuracy   | 98.00%  |
| Test Accuracy  | ~98.00% |
