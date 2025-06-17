# 🐱🐶 Cat vs Dog Classifier (CNN Model)

This is a deep learning image classification project that classifies images of cats and dogs using a Convolutional Neural Network (CNN). Built using TensorFlow and Keras.

---

---

## 🚀 Features

- Built using **CNNs with TensorFlow/Keras**
- Data preprocessing with `ImageDataGenerator`
- Image classification into two classes: **Cat** and **Dog**
- Achieves good accuracy on test set
- Visualizes training accuracy and loss

---

## 🧠 Model Architecture

```text
Conv2D (32 filters, 3x3) → ReLU → MaxPooling2D  
Conv2D (64 filters, 3x3) → ReLU → MaxPooling2D  
Flatten → Dense (128 units) → Dropout → Dense (1, sigmoid)


## 📁 Project Structure


