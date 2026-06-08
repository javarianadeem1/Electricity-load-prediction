# Electricity Load Prediction Using Regression Analysis

## Project Overview

This project demonstrates how Machine Learning can be applied to predict electricity load demand using environmental factors such as temperature and humidity. The project is developed in Python using Jupyter Notebook and Scikit-Learn.

Load forecasting is an important task in power systems because it helps utilities and grid operators plan electricity generation, improve energy management, and reduce operational costs.

---

## Objectives

* Understand the fundamentals of machine learning for power systems.
* Predict electrical load demand using weather-related features.
* Learn data preprocessing, visualization, model training, and performance evaluation.
* Build a beginner-friendly AI project relevant to Electrical Engineering.

---

## Dataset

The dataset contains:

| Feature     | Description              |
| ----------- | ------------------------ |
| Temperature | Ambient temperature (°C) |
| Humidity    | Relative humidity (%)    |
| Load        | Electricity demand (kW)  |

For learning purposes, a sample dataset was created manually within the notebook.

---

## Tools and Technologies

* Python
* Jupyter Notebook (Anaconda)
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn

---

## Machine Learning Algorithm

### Linear Regression

Linear Regression is a supervised machine learning algorithm used to model the relationship between independent variables and a dependent variable.

In this project:

Inputs:

* Temperature
* Humidity

Output:

* Electricity Load

---

## Project Workflow

1. Import required libraries
2. Create and load dataset
3. Perform exploratory data analysis
4. Visualize relationships between variables
5. Split data into training and testing sets
6. Train Linear Regression model
7. Predict electricity load
8. Evaluate model performance
9. Visualize actual vs predicted values
10. Save trained model for future use

---

## Evaluation Metrics

The model performance is evaluated using:

### Mean Absolute Error (MAE)

Measures the average prediction error.

### Mean Squared Error (MSE)

Penalizes larger prediction errors.

### R² Score

Measures how well the model explains the variance in the data.

A value close to 1 indicates strong predictive performance.

---

## Sample Results

The model successfully learns the relationship between weather conditions and electricity demand.

Typical results:

* Low MAE
* Low MSE
* R² close to 1.0

This indicates that the model can accurately estimate electrical load for unseen data.

---

## Project Structure

Electricity_Load_Prediction/

├── Electricity_Load_Prediction.ipynb

├── load_prediction_model.pkl

├── README.md

└── requirements.txt

---

## Installation

Clone the repository:

git clone https://github.com/yourusername/Electricity_Load_Prediction.git

Move into the project directory:

cd Electricity_Load_Prediction

Install dependencies:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook

Open:

Electricity_Load_Prediction.ipynb

---

## Example Prediction

Input:

Temperature = 37°C

Humidity = 40%

Output:

Predicted Electrical Load ≈ 320 kW

(The actual value may vary depending on the trained model.)

---

## Applications

* Smart Grids
* Energy Management Systems
* Power System Planning
* Demand Forecasting
* Renewable Energy Integration
* Utility Load Management

---

## Future Enhancements

* Real-world utility datasets
* Hourly load forecasting
* Random Forest Regression
* XGBoost Regression
* Artificial Neural Networks
* LSTM Deep Learning Models
* Renewable Energy Forecasting
* Smart Grid Analytics

---

## Author

Javaria Nadeem

Electrical Engineer | AI & Machine Learning Enthusiast

This project was developed as a beginner-level machine learning application in the field of Electrical Engineering and Power Systems.
