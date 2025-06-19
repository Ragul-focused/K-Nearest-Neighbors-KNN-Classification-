# 🌸 Iris Flower Classification Using K-Nearest Neighbors (KNN)

This project is part of the AI & ML Internship Task 6. It focuses on implementing the **K-Nearest Neighbors (KNN)** algorithm to classify different species of Iris flowers based on their physical features. KNN is a simple yet powerful **instance-based learning** algorithm that uses distance metrics to make predictions.

---

## 🎯 Objective

- Implement the KNN classification algorithm using `scikit-learn`
- Normalize features for distance-based learning
- Experiment with different values of K
- Evaluate using accuracy, confusion matrix, and classification report
- Visualize the decision boundary (2D)

---

## 📁 Dataset

- **Source:** [Iris Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/iris)
- **Classes:**
  - Iris Setosa
  - Iris Versicolour
  - Iris Virginica
- **Features:**
  - Sepal length & width
  - Petal length & width

---

## 🛠 Tools Used

- Python
- Jupyter Notebook
- Pandas & NumPy for data handling
- Scikit-learn for modeling
- Matplotlib & Seaborn for plotting

---

## 🚀 Steps Performed

### 1. Data Loading & Exploration
- Loaded dataset using `sklearn.datasets.load_iris`
- Visualized class distributions and feature relationships

### 2. Data Normalization
- Standardized all numeric features using `StandardScaler`
- KNN is sensitive to feature scales (Euclidean distance)

### 3. Train-Test Split
- 80% training, 20% testing using `train_test_split`

### 4. KNN Model Training
- Used `KNeighborsClassifier` from `sklearn`
- Started with `k = 3`

### 5. Evaluation
- Evaluated accuracy and confusion matrix
- Printed classification report with precision, recall, F1-score

### 6. K Value Tuning
- Tested values of K from 1 to 20
- Plotted error rate vs. K

### 7. (Optional) Decision Boundary Visualization
- Used first 2 features to visualize how KNN separates classes

---

## 📊 Results

| Metric       | Value      |
|--------------|------------|
| Best K       | 3          |
| Accuracy     | 0.97       |
| ROC/PR Curves | N/A (multi-class) |

> The model achieved near-perfect classification on the Iris dataset with k=3. Decision boundaries clearly separate the three species.

---

## 📈 Visuals


### 📌 K vs Error Rate![Screenshot 2025-06-19 170701](https://github.com/user-attachments/assets/840585ae-9d4b-4083-ba1e-644b4d25a389)


### 📌 Decision Boundary (k=3)
![Decision Boundary]![Screenshot 2025-06-19 170809](https://github.com/user-attachments/assets/4a88d480-8482-4834-9e11-f7b4d0584958)


---

## 🧠 Key Concepts

- **KNN Algorithm:** Classifies a point based on majority vote of its k nearest neighbors
- **Normalization:** Critical for meaningful distance calculations
- **Choosing K:** Low K → overfitting, High K → underfitting
- **Distance Metric:** Euclidean distance is used by default

---


