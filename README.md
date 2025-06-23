
# 🩺 Diabetes Prediction System using Django & Machine Learning

A web-based application that predicts whether a person is likely to have diabetes using a machine learning model. The system is developed using the Django web framework and trained on the Pima Indians Diabetes dataset.

---

## 🚀 Features

- Built with Django (Python web framework)
- Real-time diabetes prediction using a trained ML model
- Clean and responsive frontend form for input
- Reads input: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, and Age

---

## 🧠 ML Model Details

- **Algorithm**: Decision Tree Classifier
- **Dataset**: Pima Indians Diabetes Dataset (`diabetes.csv`)
- **Model File**: `model.pkl`
- **Libraries Used**:
  - pandas
  - numpy
  - scikit-learn
  - joblib

---

## 💻 Tech Stack

| Component      | Technology       |
|----------------|------------------|
| Backend        | Django (Python)  |
| Frontend       | HTML, Bootstrap  |
| ML Framework   | scikit-learn     |
| Dataset        | CSV (Pima Indians) |
| Version Control| Git & GitHub     |


## Project Structure

DibetesPrediction/
│
├── predict/                 # Django app
│   ├── views.py
│   ├── urls.py
│   └── templates/
│       └── predict_form.html
│
├── DibetesPrediction/       # Django project settings
│   ├── settings.py
│   ├── urls.py
│
├── diabetes.csv             # Dataset (if used locally)
├── model.pkl                # Trained ML model
├── requirements.txt         # Python dependencies
└── README.md                # This file


## 📦 Installation & Setup

### 🔧 Clone the Repository

```bash
git clone https://github.com/ItsPratiksha31/Dibetes-Prediction-System.git
cd diabetes-prediction-django
python manage.py runserver
http://127.0.0.1:8000/

