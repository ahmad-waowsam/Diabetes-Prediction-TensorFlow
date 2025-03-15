# Diabetes-Prediction-TensorFlow

This repository contains a **neural network model** for diabetes classification using the **Pima Indians Diabetes Dataset**. The model is implemented in **TensorFlow** with **batch normalization, dropout, and early stopping**. **Hyperparameter tuning using Grid Search** improved accuracy by **7-8%**.

## 📌 Dataset
The dataset includes the following medical diagnostic features:
- **Glucose level**
- **Blood pressure**
- **BMI (Body Mass Index)**
- **Age**
- **Insulin levels**
- **Pregnancies**
- **Skin thickness**
- **Diabetes pedigree function**

Each record is labeled as **diabetic (1) or non-diabetic (0)**.

## 🚀 Approach

### 🔹 1. Data Preprocessing
- Handled **missing values** and applied **feature scaling**
- Split data into **70% train, 10% validation, and 20% test**

### 🔹 2. Neural Network Model
- **Three dense layers** with **ReLU activation**
- **Batch normalization & dropout** for stability
- **Binary cross-entropy loss** and **Adam optimizer**
- **Early stopping** to prevent overfitting

### 🔹 3. Model Evaluation
- Computed **confusion matrix, precision, recall, and F1-score**

### 🔹 4. Feature Importance Analysis
- Used **SHAP** and **Permutation Importance** to analyze feature contributions

### 🔹 5. Hyperparameter Tuning
- Optimized **neurons, learning rate, batch size, and epochs** using **Grid Search**

## 🎯 Results
- **Initial accuracy**: ~67%
- **Tuned accuracy**: ~74-75%
- **SHAP analysis**: **Glucose level, BMI, and age** were the most influential features

## 🔧 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Diabetes-Prediction-TensorFlow.git
