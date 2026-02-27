# ⚡ Power Plant Energy Output Prediction using PyTorch

## 📌 Project Overview

This project implements an Artificial Neural Network (ANN) using PyTorch to predict the electrical energy output of a Combined Cycle Power Plant.

The model learns nonlinear relationships between environmental conditions and the power produced.

---

## 📊 Dataset Description

The dataset contains the following input features:

- Temperature (AT)
- Exhaust Vacuum (V)
- Ambient Pressure (AP)
- Relative Humidity (RH)

### 🎯 Target Variable:
- Electrical Energy Output (PE)

The dataset consists of 6 years of real-world operational data from a power plant.

---

## 🧠 Model Architecture (PyTorch)

The ANN model includes:

- Input Layer (4 features)
- Hidden Layers with ReLU activation
- Output Layer (Single neuron for regression)

### Loss Function:
- Mean Squared Error (MSELoss)

### Optimizer:
- Adam Optimizer

---

## ⚙️ Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 🚀 Project Workflow

1. Data Loading and Exploration
2. Data Preprocessing
   - Train-Test Split
   - Feature Scaling (StandardScaler)
3. PyTorch Tensor Conversion
4. Model Building
5. Model Training
6. Model Evaluation

---

## 📈 Model Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

The model demonstrates strong predictive capability for regression tasks involving industrial data.

---

---

## 📉 Training Performance

The following graph shows the training loss (MSE) decreasing over epochs, demonstrating effective learning and convergence of the ANN model.

<img width="776" height="564" alt="Screenshot 2026-02-27 115805" src="https://github.com/user-attachments/assets/fc86c5e4-e9b6-41b2-af7e-f40bc91a885c" />


---

---

## 🔍 Key Learnings

- Implementing ANN from scratch using PyTorch
- Understanding forward and backward propagation
- Working with tensors and autograd
- Regression model evaluation techniques
- Importance of feature scaling in neural networks

---

## 🔮 Future Improvements

- Hyperparameter tuning
- Early stopping implementation
- Learning rate scheduling
- Comparison with other regression models (XGBoost, Random Forest)
- Model deployment using Streamlit or Flask

---

## 🤝 Connect

If you found this project interesting or have suggestions, feel free to connect!

