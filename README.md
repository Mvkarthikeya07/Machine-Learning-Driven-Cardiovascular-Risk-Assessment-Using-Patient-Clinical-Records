<div align="center">

# ❤️ Machine Learning–Driven Cardiovascular Risk Assessment Using Patient Clinical Record

### A Machine Learning–Based Clinical Risk Prediction Web Application

<p>
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-Web%20App-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-ML%20Model-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
</p>

**HeartHealthAI** — turning structured clinical data into real-time, decision-support predictions.

</div>

---

## 📑 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Objectives](#-objectives)
- [🚀 Key Features](#-key-features)
- [🧠 Machine Learning Approach](#-machine-learning-approach)
- [🏗️ Project Structure](#️-project-structure)
- [🔄 Application Workflow](#-application-workflow)
- [🖥️ Application Screenshots](#️-application-screenshots)
- [⚙️ Installation & Usage](#️-installation--usage)
- [🧪 Technologies Used](#-technologies-used)
- [🔬 Technical Highlights](#-technical-highlights)
- [🏢 Internship Experience](#-internship-experience)
- [⚠️ Disclaimer](#️-disclaimer)
- [👤 Author](#-author)
- [📜 License](#-license)
- [⭐ Final Remarks](#-final-remarks)

---

## 📌 Overview

**HeartHealthAI** is a machine learning–powered web application that predicts the risk of heart disease based on patient clinical data. The system uses a trained classification model to analyze multiple health indicators and provide a real-time prediction through a clean and intuitive web interface.

This project demonstrates a complete end-to-end ML workflow, combining data preprocessing, model training, serialization, and deployment using Flask. It is designed to showcase how machine learning models can be integrated into decision-support systems in a structured, modular, and reproducible way.

---

## 🎯 Objectives

- Build a binary classification model for heart disease risk prediction
- Apply consistent data preprocessing and feature transformation
- Deploy the trained model for real-time predictions
- Maintain a clean, modular, and scalable architecture
- Demonstrate applied machine learning in a healthcare-oriented use case

---

## 🚀 Key Features

✔ Machine learning–based heart disease risk prediction
✔ Real-time inference via web application
✔ Structured patient data input form
✔ Clear and user-friendly prediction report
✔ Modular preprocessing and training pipeline
✔ Reusable pre-trained model

---

## 🧠 Machine Learning Approach

The project follows a supervised learning classification pipeline.

### Methodology

| Stage | Description |
|---|---|
| **Dataset** | Structured clinical dataset containing patient health parameters |
| **Data Preprocessing** | Feature transformation and encoding; ensuring consistent preprocessing during training and inference |
| **Model Training** | Classification model trained on historical clinical data; performance validated during training phase |
| **Model Persistence** | Trained model serialized for reuse during inference |
| **Prediction** | User inputs are preprocessed and passed to the trained model; model outputs a risk classification (Low Risk / High Risk) |

This pipeline ensures consistency, reliability, and reproducibility.

---

## 🏗️ Project Structure

```
heart_disease_prediction/
│
├── __pycache__/
│
├── data/
│   └── heart.csv                    # Dataset used for training
│
├── models/
│   └── heart_model.pkl              # Trained ML model
│
├── notebooks/
│   └── heart_disease.ipynb          # Exploratory analysis & experiments
│
├── scripts/
│   └── train_model.py               # Model training script
│
├── static/
│   └── images/
│       └── hospital_bg.jpg          # UI background image
│
├── templates/
│   ├── index.html                   # Patient data input form
│   └── result.html                  # Prediction result page
│
├── preprocess.py                    # Data preprocessing logic
├── app.py                           # Flask application entry point
│
├── requirements.txt                 # Python dependencies
└── README.md                        # Project documentation
```

---

## 🔄 Application Workflow

1. User enters patient clinical details
2. Input data is passed through the preprocessing pipeline
3. Preprocessed data is fed into the trained ML model
4. Prediction result is generated and displayed instantly

---

## 🖥️ Application Screenshots

### Patient Data Input Interface

<img width="1366" height="768" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/e75f8987-fc15-4c17-8c3f-0b78296b34da" />

*Interface for entering patient clinical and physiological parameters.*

### Prediction Result – High Risk

<img width="1366" height="768" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/922b7aaa-ec4d-4578-9fbf-2e3a66cb5db0" />

*Displays a High Risk of Heart Disease prediction with patient details.*

### Prediction Result – Low Risk

<img width="1366" height="768" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/f124ae67-914f-4632-8714-a1c7475c0a26" />

*Displays a Low Risk / Normal prediction based on model inference.*

---

## ⚙️ Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone <your-repository-url>
cd heart_disease_prediction
```

### 2️⃣ Create a Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate    # Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application
```bash
python app.py
```

### 5️⃣ Access the Web App
```
http://127.0.0.1:5000
```

---

## 🧪 Technologies Used

- Python 3.10+
- Flask
- Scikit-learn
- Pandas
- NumPy
- Pickle
- HTML & CSS

---

## 🔬 Technical Highlights

- Consistent preprocessing between training and inference
- Serialized ML model for efficient reuse
- Clear separation of ML logic and web logic
- Notebook-based experimentation with script-based training
- Easily extensible to advanced healthcare ML applications

---

## 🏢 Internship Experience

| Field | Detail |
|---|---|
| **Role** | Machine Learning Intern |
| **Organization** | Skillfied Mentor (Edgenius Skillfied Mentor Pvt. Ltd.) |
| **Duration** | December 2025 – January 2026 (1 Month) |

This project was developed applying ML practices and professional standards from my internship at **Skillfied Mentor**. Key skills exercised:

- Applied supervised regression to real-world, multi-feature clinical datasets
- Practiced rigorous data preprocessing including missing value handling and leakage prevention
- Evaluated models using R² and RMSE for healthcare generalization
- Followed industry-standard workflows: clean train/inference separation, reproducible pipelines
- Translated statistical ML models into accessible, user-facing decision-support tools

🔗 **Certificate:** [View on LinkedIn](https://www.linkedin.com/posts/m-v-karthikeya-b26a2131b_machinelearning-artificialintelligence-datascience-activity-7421145705332760576-aka0?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFEhlw4BT-6V0rnLIZSzBIoK7YvV2QlbHLc)

---

## ⚠️ Disclaimer

This application is intended for **educational and demonstration purposes only**.
It should not be used as a substitute for professional medical diagnosis or treatment.

---

## 👤 Author

**M V Karthikeya**
Computer Science Engineer
Interests: Machine Learning, Healthcare AI, Data Science

GitHub: [https://github.com/Mvkarthikeya07](https://github.com/Mvkarthikeya07)

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Final Remarks

This project represents a well-structured, production-style machine learning application, demonstrating both technical depth and practical relevance in predictive healthcare systems.

<div align="center">

**If this project added value, consider giving it a ⭐ on GitHub!**

</div>
