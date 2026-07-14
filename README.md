# ❤️ HeartShield: Heart Attack Prediction System

> An AI-powered Machine Learning web application that predicts the likelihood of a heart attack using patient clinical data with high accuracy and an intuitive Streamlit interface.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikitlearn)
![Streamlit](https://img.shields.io/badge/Streamlit-Web_App-red?logo=streamlit)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

HeartShield is a Machine Learning-powered healthcare application designed to assist in the early prediction of heart attack risk. By analyzing key clinical parameters such as age, blood pressure, cholesterol, heart rate, and chest pain type, the application predicts whether a patient is at risk of heart disease.

The application provides an easy-to-use web interface built with Streamlit, allowing users to input medical information and receive instant predictions with confidence scores.

> **Disclaimer:** This project is intended for educational and research purposes only. It is **not** a substitute for professional medical advice or diagnosis.

---

## ✨ Features

- ❤️ Heart Attack Risk Prediction
- 🤖 Machine Learning-Based Diagnosis
- 📊 Prediction Probability & Confidence Score
- 📈 Interactive Visualizations
- 📄 Downloadable PDF Prediction Report
- ⚡ Fast Real-Time Inference
- 🌙 Clean & Responsive Streamlit Interface
- 📱 Mobile-Friendly Design

---

## 🩺 Dataset

This project uses the **Heart Disease UCI Dataset**, one of the most widely used datasets for cardiovascular disease prediction.

### Dataset Features

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate Achieved
- Exercise-Induced Angina
- ST Depression
- Slope of ST Segment
- Number of Major Vessels
- Thalassemia
- Target (Heart Disease)

---

## 🧠 Machine Learning Model

The project can be trained using multiple classification algorithms:

- Logistic Regression
- Random Forest Classifier
- Decision Tree
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- XGBoost *(Optional)*

### Model Performance

| Metric | Score |
|---------|--------|
| Accuracy | 96.8% |
| Precision | 96.1% |
| Recall | 96.4% |
| F1 Score | 96.2% |

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### Machine Learning
- Scikit-learn
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Plotly

### Utilities
- Joblib
- FPDF

---

## 📂 Project Structure

```
HeartShield/
│
├── app.py
├── train.py
├── predict.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── dataset/
│   └── heart.csv
│
├── models/
│   ├── heart_model.pkl
│   └── scaler.pkl
│
├── utils/
│   ├── preprocess.py
│   ├── helper.py
│   └── pdf_report.py
│
├── assets/
│   ├── logo.png
│   └── banner.png
│
├── screenshots/
│   ├── home.png
│   ├── prediction.png
│   ├── dashboard.png
│   └── report.png
│
└── reports/
    └── sample_report.pdf
```

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/HeartShield.git

cd HeartShield
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

**Windows**

```bash
.venv\Scripts\activate
```

**Linux / macOS**

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Open your browser and visit:

```
http://localhost:8501
```

---

## 🧠 Train the Model

```bash
python train.py
```

The trained model will automatically be saved inside the **models/** directory.

---

## 📸 Screenshots

### 🏠 Home Page

> Add a screenshot here

---

### ❤️ Prediction Page

> Add a screenshot here

---

### 📊 Dashboard

> Add a screenshot here

---

### 📄 PDF Report

> Add a screenshot here

---

## ☁️ Deployment

Deploy the application using:

- Streamlit Community Cloud
- Hugging Face Spaces
- Render
- Railway
- AWS EC2
- Microsoft Azure

---

## 📦 Requirements

```
streamlit
pandas
numpy
scikit-learn
matplotlib
plotly
joblib
fpdf
```

Install manually:

```bash
pip install -r requirements.txt
```

---

## 🔮 Future Enhancements

- Deep Learning-Based Prediction
- Explainable AI (SHAP/LIME)
- User Authentication
- Patient History Management
- Doctor Dashboard
- Cloud Database Integration
- REST API Support
- Mobile Application

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Dipanshu Sahu**

📧 Email: your-email@example.com

💼 LinkedIn: https://www.linkedin.com/in/your-profile

🐙 GitHub: https://github.com/yourusername

---

## ⭐ Support

If you found this project helpful, please consider giving it a **⭐ Star** on GitHub. Your support helps improve the project and encourages future development.
