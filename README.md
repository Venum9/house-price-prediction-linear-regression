# 🌸 Iris Flower Classification using Artificial Neural Network (TensorFlow)

## 📌 Project Overview

This project implements an **Artificial Neural Network (ANN)** using **TensorFlow/Keras** to classify Iris flowers into three different species based on their flower measurements.

The objective is to demonstrate how Deep Learning can solve multi-class classification problems using a simple feedforward neural network.

---

## 📂 Dataset

**Dataset:** Iris Dataset

The dataset contains **150 flower samples** with four numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target Classes:

- Setosa
- Versicolor
- Virginica

Dataset Shape:

- **Rows:** 150
- **Columns:** 5

No missing values were found in the dataset.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras

---

## 📚 Project Workflow

### 1. Data Loading

Loaded the Iris dataset using Pandas.

### 2. Exploratory Data Analysis

Performed:

- Dataset shape inspection
- Dataset information
- Statistical summary
- Missing value check

### 3. Data Preprocessing

- Encoded the target labels using LabelEncoder.
- Split the dataset into training and testing sets.
- Standardized the features using StandardScaler.

### 4. Building the Neural Network

A Sequential Neural Network was created with:

- Input Layer (4 Features)
- Hidden Layer (16 Neurons, ReLU)
- Hidden Layer (8 Neurons, ReLU)
- Output Layer (3 Neurons, Softmax)

### 5. Model Compilation

The model was compiled using:

- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Metric: Accuracy

### 6. Model Training

The model was trained using:

- Epochs: 50
- Batch Size: 8
- Validation Split: 20%

### 7. Model Evaluation

Performance was evaluated using:

- Accuracy
- F1 Score
- Classification Report
- Confusion Matrix

---

## 📊 Results

### Test Accuracy

**100%**

### F1 Score

**1.00**

### Classification Report

| Class | Precision | Recall | F1 Score |
|--------|-----------|--------|----------|
| Setosa | 1.00 | 1.00 | 1.00 |
| Versicolor | 1.00 | 1.00 | 1.00 |
| Virginica | 1.00 | 1.00 | 1.00 |

Overall Accuracy:

**100%**

---

## 📈 Confusion Matrix

The trained model correctly classified every flower in the testing dataset.

```
[[10 0 0]
 [0 9 0]
 [0 0 11]]
```

No misclassifications were recorded.

---

## 🧠 Key Concepts Learned

- Artificial Neural Networks (ANN)
- TensorFlow & Keras
- Sequential Models
- Dense Layers
- ReLU Activation Function
- Softmax Activation Function
- Adam Optimizer
- Sparse Categorical Crossentropy
- Feature Scaling
- Label Encoding
- Multi-Class Classification
- Model Training
- Model Evaluation

---

## 📁 Repository Structure

```
datasets/
│── iris.csv

notebooks/
│── Neural_Network_Iris_Classification.ipynb

README.md
requirements.txt
```

---

## 🚀 Future Improvements

Possible improvements include:

- Hyperparameter tuning
- Adding more hidden layers
- Implementing Dropout to reduce overfitting
- Testing different optimizers
- Applying the model to larger multi-class datasets

---

## 👩‍💻 Author

**Muhammed-Awwal Mumeenat**

Aspiring Machine Learning Engineer | AI Engineer | Front-End Developer

Currently building practical Machine Learning and Deep Learning projects while expanding my expertise in Artificial Intelligence.

---

⭐ If you found this project useful, consider giving it a star!