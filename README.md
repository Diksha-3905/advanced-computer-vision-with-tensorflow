# 🧠 Advanced Computer Vision - Class Activation Mapping (CAM) with TensorFlow

This repository contains two mini-projects demonstrating **Class Activation Mapping (CAM)** using pre-trained CNNs on:

1. 🐱🐶 **Cats vs. Dogs Dataset**
2. 👕👖 **Fashion MNIST Dataset**

Both notebooks visualize model attention using **Grad-CAM** to better understand CNN decision-making in image classification tasks.

---

## 📂 Contents

- `CatsDogs_CAM.ipynb`: Visual explanation of binary classification using MobileNetV2 and Grad-CAM on Cats vs. Dogs.
- `FashionMNIST_CAM.ipynb`: Grad-CAM on FashionMNIST with a custom CNN to inspect feature relevance.

---

## 🔍 Project Objective

To demonstrate **interpretability in CNNs** using Class Activation Maps, helping users:
- Visualize **where** the model is "looking" when classifying images
- Gain intuition about **model trust and errors**
- Learn to implement **Grad-CAM from scratch** using TensorFlow

---

## 🛠️ Technologies Used

- **Python 3.10+**
- **TensorFlow 2.x / Keras**
- NumPy, Matplotlib, OpenCV
- Grad-CAM (custom logic)

---

## 📚 Datasets

- 🐾 **Cats vs. Dogs**  
  From TensorFlow Datasets (TFDS)  
  Binary classification between cat and dog images.

- 🛍 **Fashion MNIST**  
  28x28 grayscale images of clothing items  
  Multi-class classification with 10 labels

---

## ▶️ Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/vision-cam-tensorflow.git
cd vision-cam-tensorflow
