🧠 Brain Stroke Prediction System
📌 Project Overview

The Brain Stroke Prediction System is a machine learning-based web application that predicts the likelihood of a person having a stroke based on medical and lifestyle parameters. The system provides real-time predictions along with preventive suggestions and medical recommendations.

🚀 Features
🔐 User Authentication (Login & Signup)
🧠 Stroke Risk Prediction using Machine Learning
📊 Displays Probability of Stroke
⚠️ Provides Medical Recommendations for High Risk
✅ Preventive Tips for Low Risk Users
🌐 Interactive Web Interface built with Streamlit
🛠️ Technologies Used
Frontend & UI: Streamlit
Backend: Python
Machine Learning Model: RandomForestClassifier
Data Processing: Pandas, NumPy
Model Optimization: SMOTE (to handle imbalanced dataset)
Scaling: StandardScaler
📊 Input Parameters

The model predicts stroke risk based on the following features:

Gender
Age
Hypertension
Heart Disease
Marital Status
Work Type
Residence Type
Average Glucose Level
Body Mass Index (BMI)
Smoking Status
🧠 How It Works
User logs in or creates an account
Inputs health-related details
Data is preprocessed and scaled
The trained ML model predicts stroke probability
Based on probability:
🔴 High Risk → Medical suggestions & warning signs
🟢 Low Risk → Preventive health tips
⚠️ Machine Learning Note

The dataset used for training is highly imbalanced. To address this:

SMOTE is applied to balance the dataset
Probability threshold is adjusted for better detection
Accuracy is supplemented with realistic prediction behavior
📈 Sample Output
Stroke Probability: 78%
Risk Level: High
Suggestions:
Consult a doctor immediately
Control blood pressure and sugar levels
Maintain a healthy lifestyle
📂 Project Structure
brain_stroke_project/
│
├── app.py
├── stroke_data.csv
├── users.csv
├── README.md
▶️ How to Run the Project
1. Install Dependencies
pip install streamlit pandas numpy scikit-learn imbalanced-learn
2. Run the Application
streamlit run app.py
3. Open in Browser
http://localhost:8501
