# 🚀 Network Intrusion Detection using Machine Learning & Deep Learning

## 📌 Overview
This project focuses on detecting network intrusions using both traditional Machine Learning models and Deep Learning approaches.  
The goal is to compare performance, accuracy, and training behavior across different models.

---

## 🧠 Models Implemented
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- Convolutional Neural Network (CNN)

---

## 📊 Dataset
- Network traffic dataset
- Features are preprocessed and normalized
- Large datasets are excluded from GitHub (see `.gitignore`)

> ⚠️ Due to GitHub file size limits, the dataset is **not included** in this repository.

---

## ⚙️ Preprocessing Steps
- Missing value handling
- Feature scaling using `StandardScaler`
- Train-test split
- Optional SMOTE for class imbalance handling

---

## 🏗 Model Architecture (CNN)
- Input Layer
- 1D Convolution Layer
- Max Pooling
- Flatten
- Fully Connected Dense Layer
- Sigmoid Output

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🧪 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
