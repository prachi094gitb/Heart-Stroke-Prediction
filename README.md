# ❤️ Heart Disease Prediction using Machine Learning

An end-to-end Machine Learning project that predicts the likelihood of heart disease using patient medical information. The project includes Exploratory Data Analysis (EDA), data preprocessing, comparison of multiple machine learning models, model serialization, and an interactive Streamlit web application for real-time predictions.

---

## 📌 Project Overview

Heart disease remains one of the leading causes of death worldwide. Early risk prediction can assist healthcare professionals in identifying high-risk patients and taking preventive measures.

This project builds a supervised machine learning model capable of predicting whether a patient is at risk of heart disease based on various clinical attributes.

The project follows a complete ML pipeline:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Model Training
- Model Comparison
- Model Evaluation
- Model Deployment using Streamlit

---

## 🚀 Features

- Comprehensive Exploratory Data Analysis (EDA)
- Missing value handling and data preprocessing
- Feature encoding using One-Hot Encoding
- Feature scaling with StandardScaler
- Comparison of multiple Machine Learning models
- Selection of the best-performing model
- Model persistence using Joblib
- Interactive Streamlit web application
- Real-time heart disease prediction

---

## 📂 Dataset

The dataset contains patient health records including:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression (Oldpeak)
- ST Slope
- Heart Disease (Target)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Streamlit

---

## 📊 Exploratory Data Analysis

The notebook includes:

- Dataset exploration
- Summary statistics
- Missing value analysis
- Duplicate checking
- Distribution plots
- Count plots
- Box plots
- Violin plots
- Correlation Heatmap

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Handling invalid zero values
- Feature Encoding using One-Hot Encoding
- Train-Test Split
- Feature Scaling using StandardScaler

---

## 🤖 Machine Learning Models Compared

The project compares the performance of multiple classification algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree Classifier
- Gaussian Naive Bayes

Models were evaluated using:

- Accuracy Score
- F1 Score

The best-performing model was selected and saved using Joblib for deployment.

---

## 📈 Model Evaluation

Evaluation metrics used:

- Accuracy
- F1 Score
- Classification Report
- Confusion Matrix

---

## 💻 Streamlit Application

A user-friendly Streamlit web application allows users to:

- Enter patient medical information
- Predict heart disease risk instantly
- Receive predictions using the trained machine learning model

---


## ▶️ Run Locally

Clone the repository

```bash
git clone https://github.com/yourusername/Heart-Disease-Prediction.git
```

Navigate to the project

```bash
cd Heart-Disease-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature importance analysis
- Explainable AI (SHAP/LIME)
- Cloud deployment
- Deep learning implementation

---

## 👩‍💻 Author

**Prachi Sinha**

B.Tech CSE (AI & ML)

Passionate about Machine Learning, Data Science, and AI-driven solutions.

---

⭐ If you found this project useful, consider giving the repository a star!