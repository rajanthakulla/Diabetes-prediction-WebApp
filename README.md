# Diabetes-Prediction-Web-App
A trained Support Vector Machine (SVM)  model will detect whether you have diabetes or not.
check the App here https://diabetespredicting.streamlit.app/
# Diabetes Prediction Web App

This web application is designed to predict whether a person is diabetic or not based on input parameters. It uses a machine learning model trained on diabetes-related data.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- Python 3.x
- Streamlit
- NumPy
- Pickle

You can install the required dependencies using the following command:

pip install streamlit numpy

## Installation

1.Clone the repository:
  git clone https://github.com/Aks-hit/diabetes-prediction-app.git
  
  cd diabetes-prediction-app

2.Run the application:
  streamlit run app.py

The web app will be accessible in your browser at http://localhost:8501.

## Usage

1.Enter the required information such as the number of pregnancies, glucose level, blood pressure, etc.

2.Click the "Diabetes Test Result" button to get the prediction.

3.The result will be displayed indicating whether the person is diabetic or not.

## Model

  The machine learning model used for prediction is stored in the file trained_model.sav. It is loaded using the pickle library.

## Contributing

  Feel free to contribute to the project by opening issues or submitting pull requests. Your contributions are welcome!
