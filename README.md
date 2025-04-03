## 🚀 Sensor-Fault-Detection Machine learning project
A Machine Learning project for detecting sensor faults using a Random Forest classifier. The model predicts whether a sensor is faulty (1) or functioning correctly (0).

## 📌 Project Overview
Sensors play a crucial role in various industrial and IoT applications. Detecting faulty sensors early helps prevent system failures and ensures operational efficiency. This project builds a binary classification model using the Random Forest algorithm to identify sensor faults based on collected data.

## 📊 Dataset
The dataset consists of sensor readings collected from various sources.
Features include temperature, pressure, humidity, vibration levels, etc.

Target variable:

0 → No Fault
1 → Fault Detected

## 🔥 Model & Techniques
Random Forest Classifier for binary classification

Feature engineering & selection

Handling missing values & outliers

Hyperparameter tuning using GridSearchCV

Model evaluation using Accuracy, Precision, Recall, F1-score, and AUC-ROC

## 📌 Results & Performance
Achieved 100% accuracy on test data.
Model successfully detects sensor faults with high recall.

## 💡 Future Enhancements
Implement deep learning-based approaches for better performance.
Deploy the model using Flask/FastAPI for real-time predictions.
Integrate with IoT systems for live monitoring.

