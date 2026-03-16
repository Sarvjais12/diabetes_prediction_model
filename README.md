# 🩺 Diabetes Risk Prediction AI

### **Machine Learning Diagnostic Tool with Class Balancing**
[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/Sarvjais12/diabetes-prediction-app)

A machine learning-powered web application designed to predict the likelihood of diabetes based on standard medical metrics. Trained on the **Pima Indians Diabetes Dataset**, this project emphasizes end-to-end ML pipeline development, from handling imbalanced data to deploying an interactive web interface.

---

## 🚀 Key Features

* **Algorithmic Optimization**: Transitioned from a baseline `MLPClassifier` (Neural Network) to a robust `RandomForestClassifier` to better handle tabular feature relationships and improve interpretability.
* **Bias Mitigation (Data Balancing)**: Identified a severe class imbalance in the original dataset (500 Non-Diabetic vs. 268 Diabetic records) causing false-negative predictions. Applied **data upsampling** to the minority class to restore predictive fairness and accuracy.
* **Real-Time Clinical UI**: Deployed an intuitive Gradio web interface allowing users to input medical vitals and receive instantaneous diagnostic predictions.
* **Zero-Setup Deployment**: Hosted live on Hugging Face Spaces for immediate access and demonstration.

---

## 🧠 Model Architecture & Input Features

The model analyzes 8 physiological health indicators to output a binary prediction:

| Feature | Description |
| :--- | :--- |
| **Pregnancies** | Number of times pregnant |
| **Glucose** | Plasma glucose concentration (2 hours in an oral glucose tolerance test) |
| **Blood Pressure** | Diastolic blood pressure (mm Hg) |
| **Skin Thickness** | Triceps skin fold thickness (mm) |
| **Insulin** | 2-Hour serum insulin (mu U/ml) |
| **BMI** | Body Mass Index (weight in kg / (height in m)^2) |
| **Pedigree Function** | Diabetes pedigree function (genetic risk score) |
| **Age** | Age in years |

**Target Output:**
* `0` 🟢 → Non-Diabetic
* `1` 🔴 → Diabetic

---

## 🛠️ Tech Stack

* **Programming Language**: Python 🐍
* **Machine Learning Framework**: Scikit-Learn
* **Data Processing**: Pandas, NumPy (Upsampling & Preprocessing)
* **Web UI Framework**: Gradio
* **Cloud Deployment**: Hugging Face Spaces

---

## 📋 Professional Context

This project highlights core competencies in **Applied Machine Learning**. Rather than blindly trusting initial model outputs, I conducted an error analysis, identified the imbalanced dataset as the root cause of overpredicting the majority class, and applied statistical upsampling to correct the model's behavior. 

---

## 💻 How to Run Locally

1. Clone the repository:
   ```bash
   git clone [https://github.com/sarvjais12/Diabetes-Prediction-App.git](https://github.com/sarvjais12/Diabetes-Prediction-App.git)
   cd Diabetes-Prediction-App
Install dependencies:

Bash
pip install scikit-learn gradio pandas numpy
Launch the app:

Bash
python app.py
Open the local URL provided in your terminal to interact with the model.

Author: Sarvagya Jaiswal

B.Tech CSE Student | Specialization in AI/ML [LinkedIn] | [GitHub]
