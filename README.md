# 🫀 Heart Disease Risk Prediction System

This web application predicts the likelihood of heart disease based on user inputs such as age, sex, chest pain type, cholesterol levels, and more. It uses a machine learning model trained on medical data to provide predictions with confidence scores.

## 🚀 Features

- 🏥 Predicts heart disease risk with confidence
- 📊 Uses a trained machine learning model (`model.pkl`)
- 🔠 Categorical input encoding via `encoders.pkl`
- 💻 Built with Python and Flask
- 🎨 Responsive and modern UI with HTML/CSS
- 🧼 Input validation and error handling
- 🔁 Auto-reset of form after each submission

## 🧠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python     | Backend & ML logic |
| Flask      | Web framework |
| HTML/CSS   | Frontend UI |
| scikit-learn | Machine Learning |
| NumPy & Pandas | Data processing |
| joblib     | Model and encoder serialization |

## 📂 Files Included

- `app.py`: Flask backend
- `model.pkl`: Trained ML model
- `encoders.pkl`: Label encoders for categorical fields
- `templates/index.html`: UI with patient form and result
- `requirements.txt`: Python dependencies

## 🧪 How to Run Locally

1. **Clone the Repository**

```bash
git clone https://github.com/umarsubhani369/Heart-Disease-Risk-Prediction.git
cd Heart-Disease-Risk-Prediction

Install Requirements
pip install -r requirements.txt

Run the Flask App
python app.py

