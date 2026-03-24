# Parkinson’s Disease Prediction using Voice Data

## 🚀 Overview
This project is a machine learning-based system designed to detect Parkinson’s disease using biomedical voice measurement data.

## 🧠 Key Features
- Early detection using voice signal features
- Multiple ML models for classification
- Data preprocessing and feature selection
- Model evaluation using standard metrics

## 🎤 Voice Data Used
The system uses biomedical voice measurement data containing features such as:
- Frequency variation
- Amplitude variation
- Vocal signal irregularities

These features help identify patterns associated with Parkinson’s disease.

## ⚙️ Technologies Used
- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn

## 🤖 Models Used
- Support Vector Machine (SVM)
- Random Forest
- K-Nearest Neighbors (KNN)
- Logistic Regression

## 🔄 Workflow

```mermaid
graph TD
A[Voice Data Input] --> B[Data Preprocessing]
B --> C[Feature Selection]
C --> D[Model Training]
D --> E[Model Evaluation]
E --> F[Prediction Output]
