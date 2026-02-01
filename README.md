# Artificial Neural Networks (ANN) – Project Portfolio 🧠

This repository contains multiple projects implemented using **Artificial Neural Networks (ANN)**.  
The goal of this repository is to demonstrate the practical application of ANN models for **classification and regression problems** using real-world and benchmark datasets.

---

## 📁 Projects Included

---

### 1️⃣ Credit Card Customer Churn Prediction using ANN
📌 **Problem Statement:**  
Predict whether a credit card customer is likely to churn (close their account) based on demographic details, credit usage behavior, and transaction patterns.

📊 **Dataset Description:**
- Customer age, gender, education level
- Credit limit and account balance
- Transaction count and transaction amount
- Relationship tenure with the bank
- Inactive months and behavioral metrics

🛠 **Methodology:**
- Data cleaning and preprocessing
- Encoding categorical features
- Feature scaling using standardization
- ANN architecture with:
  - Fully connected hidden layers (ReLU activation)
  - Output layer with sigmoid activation
- Binary Cross-Entropy loss
- Adam optimizer

📈 **Evaluation Metrics:**
- Accuracy
- Training and validation loss analysis

🎯 **Outcome:**  
The model effectively identifies customers at high risk of churn, enabling banks to design targeted retention strategies.

---

### 2️⃣ GRE Admission Prediction using ANN
📌 **Problem Statement:**  
Predict the probability of admission into a graduate program based on academic performance and profile attributes.

📊 **Dataset Features:**
- GRE Score
- TOEFL Score
- University Rating
- SOP & LOR strength
- CGPA
- Research Experience

🛠 **Methodology:**
- Feature normalization
- ANN-based regression model
- Mean Squared Error (MSE) loss function
- Adam optimizer

📈 **Evaluation Metrics:**
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- r2 score
- Loss vs Epoch curve

🎯 **Outcome:**  
Helps applicants estimate their chances of admission and understand the impact of different profile parameters.

---

### 3️⃣ Handwritten Digit Classification using ANN
📌 **Problem Statement:**  
Classify handwritten digits (0–9) using pixel intensity values from images.

📊 **Dataset:**
- MNIST Handwritten Digit Dataset

🛠 **Methodology:**
- Image normalization and flattening
- Multi-class ANN architecture
- ReLU activation in hidden layers
- Softmax activation in output layer
- Categorical Cross-Entropy loss

📈 **Evaluation Metrics:**
- Classification accuracy


🎯 **Outcome:**  
Demonstrates the effectiveness of ANN models in image classification and pattern recognition tasks.

---

## 🧠 Technologies & Tools Used
- Python
- NumPy
- Pandas
- Matplotlib & Seaborn
- TensorFlow / Keras
- Jupyter Notebook

---

## 🎯 Learning Objectives
- Understand ANN architecture and training
- Apply ANN to classification and regression problems
- Perform data preprocessing suitable for neural networks
- Evaluate model performance and analyze results

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repository-link>

## ⭐ Note
These projects are implemented as part of hands-on learning and demonstrate practical understanding of
Artificial Neural Networks for real-world classification and regression problems.
