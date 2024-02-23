# Iris Detection ML Model

This repository contains code for a simple Iris detection machine learning model deployed using Streamlit. The model classifies Iris flowers into three categories: Setosa, Versicolor, and Virginica based on their sepal and petal dimensions.

## Usage

To use the deployed model, visit [Iris Detection Model](https://irisdetectionmodel.streamlit.app/).

## Requirements

- Python 3.x
- Streamlit
- Pandas
- Numpy
- Scikit-learn

## Description

The application consists of a Streamlit interface where users can adjust sliders to input sepal and petal characteristics (length and width) of an Iris flower. Upon clicking the "Predict type of Iris" button, the model predicts the type of Iris based on the provided features.

## Development

The model was trained using a Random Forest Classifier on the Iris dataset. The training script (`train.py`) reads the dataset, splits it into training and testing sets, trains the model, and evaluates its accuracy. The trained model is saved as `rf_model.sav` using joblib.

## Deployed Application

The deployed application is hosted at [Iris Detection Model](https://irisdetectionmodel.streamlit.app/). Users can interact with the model through a web interface to classify Iris flowers.

## Files

- `prediction.py`: Contains the function to make predictions based on user input.
- `app.py`: Script to train the machine learning model.
- `requirements.txt`: Lists the required dependencies.
- `rf_model.sav`: Saved trained Random Forest Classifier model.
- `iris.csv`: Iris dataset used for training.

## Usage

To run the Streamlit application locally:

1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Streamlit app using `streamlit run app.py`.
4. Access the application through the provided local URL.

Feel free to explore and contribute to this repository!
