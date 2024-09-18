# Forest Fire ML Flask App

This repository contains a Flask-based web application for predicting data points using a Ridge Regression model. The app loads a pre-trained Ridge Regression model and a Standard Scaler (both stored in `.pkl` files) to make predictions based on user input.

## Features

- User-friendly web interface built with Flask.
- The app predicts outcomes using a Ridge Regression model based on various input features like temperature, humidity, wind speed, rain, etc.
- The data is first preprocessed using a standard scaler before making predictions.
  
## Project Structure

- `app.py`: Main Flask application file that includes route definitions and model prediction logic.
- `models/ridge.pkl`: Pre-trained Ridge Regression model stored as a pickle file.
- `models/scaler.pkl`: Standard Scaler used for normalizing input data stored as a pickle file.
- `templates/index.html`: HTML template for the homepage.
- `templates/home.html`: HTML template for displaying prediction results.

## Installation and Setup

### Prerequisites

Ensure that you have the following installed:

- Python 3.x
- Flask
- Scikit-learn
- Pandas
- NumPy
- Pickle

