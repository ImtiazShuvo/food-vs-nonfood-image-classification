# Food vs Non-Food Image Classification

Deep learning project for **binary image classification** using:

- Custom **Convolutional Neural Network (CNN)**
- **Residual CNN (ResNet-style architecture)**
- **Transfer Learning with EfficientNetB0**

The models are trained using **TensorFlow / Keras** on the **Food-5K dataset**.

This project compares how **different neural network architectures** perform on image classification tasks and how **transfer learning improves performance**.

---

# Author

**Md Imtiaz Kamru**  
PhD Student — Electrical & Computer Engineering  
The University of Alabama  

---

# Project Overview

This project investigates multiple deep learning architectures for classifying images into two categories:

- **Food**
- **Non-Food**

Three different models were developed and compared to evaluate:

- Model complexity
- Feature extraction capability
- Training stability
- Generalization performance

---

#  Dataset

The project uses the **Food-5K dataset**, containing approximately **5000 labeled images**.

Classes:

- Food
- Non-Food

Images are resized to **256 × 256 pixels** during preprocessing.

Dataset source:

https://www.kaggle.com/trolukovich/food5k-image-dataset

---

# Implemented Models

## Custom CNN

A baseline convolutional neural network composed of:

- Convolution layers
- Max pooling
- Batch normalization
- Dropout regularization
- Dense classification layers

This model serves as a **baseline architecture**.

---

## Residual CNN (ResNet-style)

A deeper architecture implementing **custom residual blocks** inspired by the ResNet architecture.


Residual connections allow:

- Better gradient flow
- Deeper networks
- More stable training

---

## EfficientNetB0 Transfer Learning

A **pretrained EfficientNetB0 model** is used as a feature extractor.

Steps:

1. Load pretrained EfficientNetB0 weights
2. Freeze the backbone layers
3. Add custom classification layers
4. Train only the top layers

Advantages:

- Faster convergence
- Strong feature representation
- Reduced training data requirement

---

# Training Techniques

Several techniques were applied to improve model performance:

- **Data Augmentation**
- **Dropout Regularization**
- **Batch Normalization**
- **Transfer Learning**
- **Validation-based Model Selection**

These methods help improve **generalization and reduce overfitting**.

---

# Results

Training and validation curves were analyzed for:

- Model convergence
- Overfitting behavior
- Generalization ability

### Key Observations

- Data augmentation improved model robustness
- Dropout helped reduce overfitting
- Residual connections stabilized deep network training
- Transfer learning achieved faster convergence

---

# Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- EfficientNet
- Deep Learning / CNN

---

