# 🌱 Fertilizer Recommendation System

## 📌 Project Overview

The Fertilizer Recommendation System is a Machine Learning project that predicts a suitable fertilizer category based on soil properties, crop type, and environmental conditions.

The system uses five classification algorithms and compares their performance using standard evaluation metrics. A user-friendly web interface built with Gradio allows users to enter input values and receive a fertilizer prediction.

## 🎯 Objectives

- Recommend fertilizer categories based on input data.
- Train and compare multiple Machine Learning classification algorithms.
- Evaluate models using Accuracy, Precision, Recall, and F1-score.
- Visualize and compare model performance.
- Build an interactive web application using Gradio.

## 📊 Dataset

**Dataset:** Fertilizer Prediction Dataset (`Fertilizer Prediction.csv`)

The dataset contains soil, crop, and weather-related features.

### Input Features

- Temperature
- Humidity
- Moisture
- Soil Type
- Crop Type
- Nitrogen (N)
- Potassium (K)
- Phosphorus (P)

### Target Variable

- Fertilizer Name

## 🤖 Machine Learning Algorithms

The project evaluates the following five classification algorithms:

1. **Gaussian Naive Bayes** — predicts classes using probability.
2. **Support Vector Machine (SVM)** — separates classes using decision boundaries.
3. **K-Nearest Neighbors (KNN)** — predicts a class using nearby data points.
4. **Decision Tree** — makes predictions using a sequence of feature-based rules.
5. **Random Forest** — combines multiple decision trees for classification.

The model with the highest weighted F1-score on the selected test split is chosen for the web application's predictions.

## 📈 Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- Weighted F1-score

A performance comparison table is displayed in the application.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Gradio
- Joblib
- Matplotlib

## 🌐 Web Application

The Gradio web interface allows users to enter:

- Temperature
- Humidity
- Soil moisture
- Soil type
- Crop type
- Nitrogen
- Potassium
- Phosphorus


## 🚀 Future Improvements

- Deploy the application online.
- Add model explainability visualizations.
- Improve performance with additional data.
- Validate recommendations using agricultural expertise.
- Add input validation and clearer guidance for users.

## ⚠️ Disclaimer

This project is intended for educational and machine learning demonstration purposes. Predictions are based on the available dataset and should not be treated as guaranteed agricultural recommendations. Actual fertilizer selection depends on soil testing, crop requirements, and local agricultural guidance.

## 👨‍💻 Author
Dharmendra Kumar Singh
Github:-[("thakurdm64@gmail.com"),("https://github.com/DharmendraKumarSingh-ai")]
