# ❤️ Heart Disease Prediction

A machine learning web application that predicts the risk of heart disease based on patient health information. The application uses a trained **K-Nearest Neighbors (KNN)** model and provides an interactive interface built with **Streamlit**.

## 🚀 Live Demo

👉 **[Try the Heart Disease Prediction App](https://heart-disease-prediction98.streamlit.app/)**

## 📌 About the Project

This project demonstrates how machine learning can be integrated into an interactive web application.

Users can enter health-related information such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* Oldpeak
* ST Slope

The application processes the input using the same preprocessing pipeline used during model training and generates a heart disease risk prediction.

## 🧠 Machine Learning

The project uses a **K-Nearest Neighbors (KNN)** classification model.

The workflow includes:

1. Data preprocessing
2. Encoding categorical variables
3. Feature scaling
4. Training the KNN classifier
5. Saving the trained model using `joblib`
6. Loading the trained model in the Streamlit application
7. Generating predictions from user input

The trained model, scaler, and expected feature columns are stored as `.pkl` files and loaded by the application.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Joblib**
* **Streamlit**
* **Git & GitHub**


