🩺 Diabetes Prediction App
Welcome to the Diabetes Prediction App, a machine learning-powered web application that predicts whether a person is diabetic or not based on medical inputs.

🚀 Live App: https://huggingface.co/spaces/Sarvjais12/diabetes-prediction-app

📌 Overview
This app uses a trained Random Forest Classifier model (or MLPClassifier) to predict diabetes risk from 8 health-related input features. It was trained on the popular Pima Indians Diabetes Dataset.

🧠 Model Details
Input Features:

Pregnancies

Glucose Level

Blood Pressure

Skin Thickness

Insulin

BMI

Diabetes Pedigree Function

Age

Target Output:

0 → Non-Diabetic

1 → Diabetic

Model Used:
Initially trained using MLPClassifier from scikit-learn. Later improved using RandomForestClassifier with class balancing to address dataset bias.

⚙️ Tech Stack
Python 🐍

Scikit-learn

Gradio (for the UI)

Hugging Face Spaces (for deployment)

🖥️ How to Use the App
Enter your medical details in the Gradio interface.

Click Submit.

Get instant prediction:

"Diabetic" if model output = 1

"Not Diabetic" if model output = 0

🧪 Model Training Notes
Dataset was imbalanced (500 non-diabetic, 268 diabetic), which caused the model to overpredict diabetes.

Applied upsampling of the diabetic class to balance the training set.

Improved accuracy and fairness.

Sarvagya Jaiswal
B.Tech CSE Student | Specialization in AI/ML
LinkedIn • GitHub

📎 Live Deployment Link
✅ https://huggingface.co/spaces/Sarvjais12/diabetes-prediction-app
