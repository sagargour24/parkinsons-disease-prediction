# 🧠 Parkinson's Disease Prediction Using Machine Learning

This project leverages machine learning techniques to predict the presence of Parkinson's Disease (PD) based on biomedical voice measurements. By analyzing vocal features, the model aims to provide a non-invasive, cost-effective diagnostic tool to assist in early detection.

---

## 📂 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/parkinsons)
- **Instances**: 195
- **Features**: 22 biomedical voice measurements per instance
- **Target Variable**: `status` (1 = PD, 0 = Healthy)

---

## 🛠️ Features

- **Data Preprocessing**: Handling missing values, normalization, and feature selection  
- **Model Training**: Implementation of various classifiers including:
  - Support Vector Machine (SVM)
  - Random Forest
  - K-Nearest Neighbors (KNN)
  - Logistic Regression  
- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC Curve  
- **Visualization**: Confusion matrix, ROC curves, and feature importance plots

---

## 🚀 Getting Started

### Prerequisites

Make sure the following libraries are installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
