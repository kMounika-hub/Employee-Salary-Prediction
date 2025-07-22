
# 💼 Employee Salary Prediction using Machine Learning

This project predicts employee salaries based on user inputs like experience, education, role, and location using a trained machine learning model. The app is built using **Streamlit** and deployed at:
---

## 📌 Features

- 📊 Predict salary based on inputs like:
  - Education Level
  - Job Role
  - Experience (Years)
  - Location
- 📈 Uses trained ML model for accurate predictions
- 🧠 Machine Learning model built using `scikit-learn`
- 🚀 Deployed on **Streamlit Cloud**

---

## 🛠️ Tech Stack

- Python 🐍
- Streamlit 📺
- scikit-learn 🤖
- Pandas 📊
- Joblib (for saving ML models)

---

## 📂 Project Structure

├── app.py # Streamlit app

├── model.pkl # Trained ML model (via joblib)

├── dataset.csv # Input dataset used for training

├── requirements.txt # Python dependencies

└── README.md # Project documentation

---
#Installestion

pip install -r requirements.txt

streamlit run app.py

📊 Dataset
The dataset includes employee information such as:

Role

Experience

Education

Location

Current Salary (Target Variable)

(Ensure your dataset is preprocessed appropriately for training and predicting.)
🤖 Model
A regression model is trained using:

Linear Regression or Random Forest

OneHotEncoder for categorical features

StandardScaler for numerical features

Saved using joblib and loaded in the app.py script for prediction.

📸 App Preview

Simple user-friendly interface for salary prediction.

✨ Acknowledgments
Thanks to:

Streamlit for the easy deployment.

Open-source community for inspiration and resources.

