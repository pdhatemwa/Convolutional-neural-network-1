# Convolutional Neural Network for Digit Recognition

> First CNN project for learning image recognition by classifying digits (0–9).

---

## 📌 Overview
This project implements a **Convolutional Neural Network (CNN)** to recognize digits in images. Given an image of a number (e.g., 2), the model predicts the corresponding digit.

---

## 🎯 Objectives
- Learn the fundamentals of CNNs
- Build an end-to-end image classification pipeline
- Train and evaluate a digit recognition model

---

## 🧠 Model Summary
- Input: 28×28 grayscale images
- Convolution + Max Pooling layers
- Fully connected layers
- Softmax output for 10 classes (0–9)

---

## 📊 Dataset
- **MNIST** handwritten digit dataset
- 60,000 training images
- 10,000 test images

---

## 🛠️ Technologies
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

## 📁 Project Structure
```text
convolutional-neural-network/
│── data/
│── src/
│   └── cnn_digit_recognition.py
│── README.md
│── requirements.txt
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/convolutional-neural-network-1.git
cd convolutional-neural-network-1
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the model
```bash
python src/cnn_digit_recognition.py
```

---

## ✅ Results
- The model is evaluated using **accuracy** on test data
- Example predictions are visualized using Matplotlib

---

## 🔮 Future Improvements
- Increase model depth
- Use custom handwritten digit images
- Add confusion matrix and performance metrics

---

## 👤 Author
**Patrick Dhatemwa**

---

## 📄 License
This project is for educational purposes.
