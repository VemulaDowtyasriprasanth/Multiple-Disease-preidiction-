# Multiple Disease Prediction
# Multiple Disease Prediction System

## Overview
The **Multiple Disease Prediction System** is a machine learning-powered web application that predicts the likelihood of three diseases—diabetes, heart disease, and Parkinson’s disease. Using pre-trained models, the application analyzes user inputs through a user-friendly interface built with Streamlit, providing predictions to aid early diagnosis.

![Architecture Diagram](Disease.png)

## Project Motivation
This project aims to contribute to the healthcare field by providing a quick, accessible tool for disease prediction based on common health indicators. This can assist individuals and healthcare professionals with early detection, improving patient outcomes and enabling timely interventions.

## Features
- **Disease Prediction Models**: Predicts the likelihood of diabetes, heart disease, and Parkinson’s disease.
- **User Interface**: Interactive web-based application built with Streamlit, allowing users to input health data and receive instant predictions.
- **Data-Driven Insights**: Each disease model is trained on disease-specific datasets, ensuring the predictions are data-backed.
- **Scalable**: The system uses pre-trained machine learning models, which can be easily updated or extended for additional diseases.

## Architecture
The application is designed in a modular structure with the following main components:

- **Frontend**: A web interface created with Streamlit for user interaction.
- **Backend**: Machine learning models for each disease, saved as `.sav` files and loaded dynamically.
- **Data Processing**: Custom preprocessing pipelines for each disease to standardize user input data.

### Prediction Models:
- **Diabetes**: SVM model trained on PIMA Diabetes Dataset.
- **Heart Disease**: Logistic Regression model trained on a heart disease dataset.
- **Parkinson’s Disease**: SVM model trained on vocal measurements for Parkinson’s detection.

## Project Structure
```bash
.
├── main.py                  # Main Streamlit app file for launching the application
├── diabetes_model.sav       # Trained model for diabetes prediction
├── heart_disease_model.sav   # Trained model for heart disease prediction
├── parkinsons_model.sav     # Trained model for Parkinson's disease prediction
├── D.csv                    # Diabetes dataset (PIMA Diabetes Dataset)
├── H.csv                    # Heart disease dataset
├── P.csv                    # Parkinson's disease dataset
├── sidebar.css              # Custom styling for Streamlit sidebar
├── style.css                # General styling for Streamlit app
├── requirements.txt         # Project dependencies
├── notebooks/
│   ├── Diabetes.ipynb       # Training notebook for Diabetes model
│   ├── Multiple_disease_prediction_system_heart.ipynb # Training notebook for Heart Disease model
│   └── Parkinsons.ipynb     # Training notebook for Parkinson's model
└── README.md                # Documentation file


## Steps To Install 


1) Install Required Libreries From the requirements.txt


> pip install -r requirements.txt


>This will install all the libraries like streamlit , pickle , streamlit_option_menu


2) Open Main.py file and set saved model paths


3) Run Streamlit for the file execution
>streamlit run main.py




4) This will launch the Streamlit web application in your default web browser.


5) Using CSV files in the directory or by manually entering the input features into the web application, provide the values for the input features such as age, blood pressure, cholesterol levels, and so on.


6) Once you have entered the required input features, the application will use the trained machine learning models to predict the likelihood of the person having diabetes, heart disease, or Parkinson's disease.


#### In summary, the Multiple Disease Prediction application is a user-friendly tool that uses machine learning algorithms to predict the likelihood of a person having diabetes, heart disease, or Parkinson's disease. By following the above steps, users can easily use this application to make informed decisions about their health.

<<<<<<< HEAD
#### Document Link : <a href="https://docs.google.com/document/d/17BQyZU0rE5WBRDx_bL8X7WOmgwfvLaJG_NXv8HkWBhs/edit?usp=sharing">Final Report Link</a>
=======
#### Document Link : <a href="https://docs.google.com/document/d/17BQyZU0rE5WBRDx_bL8X7WOmgwfvLaJG_NXv8HkWBhs/edit?usp=sharing">Final Report Link</a>
>>>>>>> 7326e7e6780f2637aed3f7b7a5c186927438e825
