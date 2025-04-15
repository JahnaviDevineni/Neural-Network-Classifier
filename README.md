# Breast Cancer Classification using Neural Network

This project implements a feedforward neural network classifier to diagnose breast cancer based on the UCI Wisconsin dataset. The model predicts whether a tumor is **malignant (M)** or **benign (B)** using various cellular features.

## 📊 Dataset

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- **Features:** 30 numeric features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
- **Target:** Binary classification — Malignant (M) or Benign (B).

## 🧠 Model Overview

- **Type:** Feedforward Neural Network (Multilayer Perceptron)
- **Framework:** TensorFlow and Keras
- **Output Layer:** 2 nodes (with softmax activation for binary classification)
- **Loss Function:** Categorical Crossentropy
- **Optimizer:** Adam

## 🔧 Steps Performed

1. Data loading and exploration
2. One-hot encoding of target labels
3. Feature normalization
4. Train-test split
5. Model architecture design
6. Model training and validation
7. Accuracy evaluation and results visualization

## 📈 Results

- Achieved high classification accuracy on the test dataset
- Plotted training loss and accuracy curves to visualize model performance

## 📂 Dependencies

```bash
pip install tensorflow scikit-learn pandas matplotlib
