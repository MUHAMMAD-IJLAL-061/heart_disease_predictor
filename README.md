❤️ Heart Disease Risk Prediction System
📌 Project Description

The Heart Disease Risk Prediction System is a machine learning–based web application designed to predict the risk of heart disease based on patient clinical data. The system uses a trained Random Forest classifier and provides real-time predictions through an interactive Streamlit web interface.

This project demonstrates the complete machine learning workflow, including data preprocessing, model training, evaluation, deployment, and logging of predictions. The application is deployed online using Streamlit Cloud and is accessible through a public URL.

🔗 Live Application:
https://heartdiseasepredictor-celq6gxizr85ksbkcdnfhx.streamlit.app/

🎯 Objectives

To develop a machine learning model capable of predicting heart disease risk

To deploy the trained model as a user-friendly web application

To allow real-time prediction based on patient input

To log predictions for analysis and demonstration purposes

To gain hands-on experience with ML deployment and cloud hosting

🧠 Machine Learning Model

Algorithm: Random Forest Classifier

Dataset: Heart Failure Dataset

Target Variable: HeartDisease (0 = No, 1 = Yes)

Performance Metrics Used:

Accuracy

Precision

Recall

F1-Score

Cross-validation

The model outputs a risk probability, which is compared against a medical threshold to classify patients as High Risk or Low Risk.

🖥️ Web Application Features

Interactive form to enter patient clinical data

Real-time heart disease risk prediction

Probability-based decision output

SQLite database logging of predictions

Clean and responsive UI built with Streamlit

Fully deployed and accessible online

🛠️ Technologies Used

Programming Language: Python

Machine Learning: scikit-learn

Web Framework: Streamlit

Database: SQLite

Model Persistence: Joblib

Data Processing: Pandas, NumPy

Deployment: Streamlit Cloud

📂 Project Structure
heart_disease_predictor/
│
├── app.py                 # Streamlit application
├── heart_model.pkl        # Trained Random Forest model
├── model_columns.pkl      # Model feature columns
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation

🚀 How to Run Locally

Clone the repository:

git clone https://github.com/your-username/heart_disease_predictor.git
cd heart_disease_predictor


Install dependencies:

pip install -r requirements.txt


Run the application:

streamlit run app.py
