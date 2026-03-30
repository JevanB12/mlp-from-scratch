# 🧠 MLP from Scratch (NumPy)

## 📌 Overview
This project implements a Multi-Layer Perceptron (MLP) from scratch using NumPy, without relying on machine learning libraries such as PyTorch or TensorFlow.

The goal is to gain a deeper understanding of how neural networks work internally, including forward propagation, backpropagation, and optimisation techniques.

---

## 🎯 Key Features
- Fully custom neural network implementation
- Forward and backward propagation
- Gradient-based learning (backpropagation)
- Momentum-based optimisation
- Learning rate annealing
- Loss and RMSE tracking
- Training visualisation using Matplotlib
- Data preprocessing (cleaning + normalization)

---

## 🧩 Architecture
The model is a deep MLP consisting of:
- Input layer
- 4 hidden layers
- Output layer

Each layer includes:
- Weights and biases
- Sigmoid activation function

---

## ⚙️ Optimisation Techniques
This implementation goes beyond basic backpropagation by including:

### 🔹 Momentum
Helps accelerate training and reduce oscillations during gradient descent.

### 🔹 Learning Rate Annealing
Gradually reduces the learning rate over time to improve convergence.

---

## 📊 Training Process
The model is trained using:
- Mean Squared Error (MSE) loss
- Gradient descent optimisation
- Epoch-based training loop

Metrics tracked:
- Loss
- Root Mean Squared Error (RMSE)

---

## 📈 Results & Visualisation
The training process is visualised using:
- Loss over time
- RMSE over time

This helps analyse convergence behaviour and model performance.

---

## 📂 Dataset
The dataset is loaded from a CSV file and undergoes:
- Type conversion
- Missing value handling
- Feature normalization

---

## 🚀 How to Run
```bash
pip install numpy pandas matplotlib
python neuralnetworks.py
