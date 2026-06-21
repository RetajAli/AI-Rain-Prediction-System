# AI Rain Prediction System

## Overview

The AI Rain Prediction System is a machine learning project developed to predict rainfall based on historical weather data. The system analyzes multiple meteorological features such as temperature, humidity, pressure, wind conditions, rainfall, and location to determine whether it will rain today or tomorrow.

The project demonstrates a complete machine learning workflow, including data preprocessing, model training, evaluation, visualization, and deployment through a graphical user interface (GUI).

---

## Features

* RainToday Prediction
* RainTomorrow Prediction
* Weather Data Preprocessing
* Missing Value Handling
* Feature Scaling
* Categorical Data Encoding
* Multiple Machine Learning Models
* Model Performance Comparison
* Feature Importance Analysis
* Confusion Matrix Visualization
* Interactive Desktop GUI
* Real-Time Weather Prediction

---

## Technologies Used

### Programming Language

* Python

### Libraries and Frameworks

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Tkinter
* Jupyter Notebook

### Machine Learning Models

* Decision Tree Classifier
* Naive Bayes (Gaussian)
* Neural Network (MLP Classifier)
* Random Forest Classifier
* Gradient Boosting Classifier

---

## Repository Structure

```text
AI-Rain-Prediction-System
│
├── Documentation
│   └── Project Documentation
│
├── Presentation
│   └── Project Presentation
│
├── Dataset
│   └── train_weather.csv
│
├── Source Code
│   └── AI.ipynb
│
├── Screenshots
│   ├── GUI Output 1
│   └── GUI Output 2
│
└── README.md
```

---

## Dataset

The project uses a historical weather dataset containing numerical and categorical weather attributes.

### Input Features

* Location
* Min Temperature
* Max Temperature
* Rainfall
* Evaporation
* Sunshine
* Wind Direction
* Wind Speed
* Humidity
* Pressure
* Cloud Coverage
* Temperature Measurements

### Target Variables

* RainToday
* RainTomorrow

---

## Data Preprocessing

The following preprocessing techniques were applied:

* Missing Value Imputation
* Label Encoding for Categorical Features
* Feature Scaling using StandardScaler
* Train-Test Split (80% Training, 20% Testing)

---

## Model Evaluation

The trained models were evaluated using:

* Accuracy Score
* Classification Report
* Precision
* Recall
* F1-Score
* Confusion Matrix

The best-performing model was selected and integrated into the graphical user interface.

---

## Visualizations

The project includes several visual analysis techniques:

* Confusion Matrices
* Feature Importance Charts
* Model Accuracy Comparison Graphs
* Decision Tree Visualization

These visualizations help understand model behavior and performance.

---

## Graphical User Interface (GUI)

A desktop GUI was developed using Tkinter to allow users to interact with the prediction system.

Users can:

* Enter weather-related features
* Select the prediction target
* Generate predictions instantly
* View prediction results through a user-friendly interface

---

## Learning Outcomes

Through this project, the following concepts were applied:

* Data Preprocessing
* Feature Engineering
* Classification Algorithms
* Model Evaluation
* Machine Learning Visualization
* GUI Development
* End-to-End AI System Development

---

## Future Enhancements

* Live Weather API Integration
* Cloud Deployment
* Mobile Application Version
* Advanced Deep Learning Models
* Real-Time Weather Forecasting
* Automated Data Collection
* Interactive Dashboard

---

## Academic Purpose

This project was developed as part of the Introduction to Artificial Intelligence course and demonstrates the practical application of machine learning techniques for weather prediction and decision support systems.
