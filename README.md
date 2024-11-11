# Student Loan Recommendation System

This Jupyter Notebook demonstrates a deep learning model to assess student loan risk based on various personal, educational, and financial features. The notebook guides through data preprocessing, building a neural network model, evaluating its performance, and making predictions. It is designed to assist with predicting student loan repayment success, which could support a recommendation system for student loans.

## Project Structure
The notebook is divided into four main sections:

### Data Preparation:
- Loads data from a student-loans.csv file.
- Defines features (X) and target (y) datasets, focusing on predicting loan repayment success through a "credit_ranking" variable.
- Prepares the data for modeling by scaling features.

### Model Building:
- Constructs a deep neural network model using TensorFlow's Keras API.
- Configures model layers, neurons, and activation functions.
- Compiles and fits the model with the binary_crossentropy loss function and adam optimizer.

### Model Evaluation and Saving:
- Evaluates the model's performance on test data.
- Exports the trained model to a .keras file for reuse.

### Prediction and Reporting:
- Reloads the saved model to make predictions.
- Saves predictions to a DataFrame and generates a classification report to assess model performance.

### Discussion on Building a Recommendation System:
- The notebook ends with a discussion on building a student loan recommendation system, outlining data requirements, filtering methods, and real-world challenges.

## Prerequisites
Ensure you have the following packages installed:
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- TensorFlow

## Usage
1. Load the Notebook: Open this notebook in Jupyter.
2. Prepare Data: Ensure the student-loans.csv file is in the working directory.
3. Run Each Section: Follow the sections sequentially, executing each cell to preprocess data, build the model, evaluate performance, and save the model.
4. Analyze Results: Review model evaluation metrics and the generated classification report for insights into performance.