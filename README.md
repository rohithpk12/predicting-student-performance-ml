# Student Performance Predictor

A Flask web application that predicts a student's mathematics score from demographic, education, and exam-performance inputs.

## Features

- Interactive browser form for student data
- Trained regression model for mathematics-score prediction
- Reusable data ingestion, transformation, training, and prediction pipelines
- Exploratory analysis and model-training notebooks
- Clean Flask interface with HTML and CSS

## Technology

- Python
- Flask
- Pandas and NumPy
- Scikit-learn, CatBoost, and XGBoost
- HTML and CSS

## Run locally

```bash
git clone https://github.com/rohithpk12/predicting-student-performance-ml.git
cd predicting-student-performance-ml
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
python app.py
```

Open `http://127.0.0.1:5000/` in your browser.

## Dataset and responsible use

The model was developed with the public *Students Performance in Exams* dataset. It is an educational project and should not be used to make real-world decisions about students.
