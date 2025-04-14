# Cardio Disease Prediction Project

This repository contains a comprehensive dataset and machine learning model designed to predict cardiovascular disease outcomes. The project aims to provide insights into predicting and diagnosing heart-related diseases based on various health metrics.

## Project Overview

The project includes:
1. **Data Collection and Preprocessing**: Cleaned and processed datasets relevant to heart disease prediction.
2. **Model Development**: A machine learning model that can predict the presence or absence of heart disease based on input features such as age, cholesterol levels, blood pressure, etc.
3. **Synthetic Data Generation**: To simulate real-world medical data for better model training and validation.
4. **Evaluation**: Model performance evaluation through various metrics.

## Files and Directories

- `Cardio_Data.csv`: The raw dataset containing real-world patient data.
- `synthetic_cardio_data.csv`: A synthetic version of the original dataset used for model training and validation.
- `data_cleaned_Cardio_Data.csv`: The preprocessed and cleaned version of the dataset.
- `cardio_data_processed.csv`: The final processed data that is ready for model training.
- `model1.ipynb`: A Jupyter notebook that implements the machine learning model, including data exploration, feature engineering, and model evaluation.
- `data_clean.ipynb`: A Jupyter notebook that performs data cleaning and preprocessing steps.

## Requirements

To run the notebooks and use the model, make sure you have the following Python libraries installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

You can install the dependencies via `pip`:


## How to Run the Code

1. Clone this repository to your local machine:
git clone https://github.com/yourusername/cardio.git

2. Navigate to the project directory:
cd cardio

3. Open the Jupyter notebook:
jupyter notebook model1.ipynb

4. Follow the steps in the notebook to train the model and evaluate its performance.

## Dataset Details

### Features:
- `Age`: Age of the patient.
- `Sex`: Gender of the patient (1 = male, 0 = female).
- `ChestPainType`: Type of chest pain experienced by the patient.
- `RestingBP`: Resting blood pressure (in mm Hg).
- `Cholesterol`: Serum cholesterol levels (mg/dl).
- `FastingBS`: Fasting blood sugar (1 = true, 0 = false).
- `RestingECG`: Resting electrocardiographic results.
- `MaxHR`: Maximum heart rate achieved during stress test.
- `ExerciseAngina`: Angina induced by exercise (1 = yes, 0 = no).
- `Oldpeak`: Depression induced by exercise relative to rest.
- `ST_Slope`: The slope of the peak exercise ST segment.

### Target:
- `HeartDisease`: Target variable (1 = heart disease, 0 = no heart disease).

## Model Description

The project uses a machine learning model to predict whether a patient has heart disease or not based on various features. The dataset is preprocessed, and features are selected for training. The final model is trained using algorithms such as logistic regression, random forests, or decision trees.

## Evaluation Metrics

The model is evaluated based on the following metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix



