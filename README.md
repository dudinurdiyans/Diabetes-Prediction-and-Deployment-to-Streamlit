![image](https://github.com/dudinurdiyans/Diabetes-Prediction-and-Deployment-to-Streamlit/assets/135699744/70ae5c3f-7069-43fa-95d8-3feba0496f0c)
# Diabetes Prediction Deployment

## Overview

This repository contains code and resources for deploying a diabetes prediction model. The model is built using the `diabetes.csv` dataset and trained in the `diabetes.ipynb` Jupyter Notebook. The trained model is saved as `diabetes_model.sav`. The deployment is done using a Streamlit app defined in `stream-diabetes.py`.

## Files

- `diabetes.csv`: Dataset used for training the diabetes prediction model.
- `diabetes.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `diabetes_model.sav`: Saved model file containing the trained diabetes prediction model.
- `requirements.txt`: File listing the Python dependencies required for running the deployment.
- `stream-diabetes.py`: Streamlit app script for deploying the diabetes prediction model.

## Instructions

1. **Data Exploration and Model Training:**
   - Open `diabetes.ipynb` in Jupyter Notebook or a compatible environment.
   - Follow the instructions in the notebook for data preprocessing, model training, and evaluation.

2. **Save the Trained Model:**
   - Ensure you have the `scikit-learn` library installed. You can install dependencies using `pip install -r requirements.txt`.
   - Run the notebook to train the model and save it as `diabetes_model.sav`.

3. **Deployment with Streamlit:**
   - Make sure you have Streamlit installed (`pip install streamlit`).
   - Run the Streamlit app using `streamlit run stream-diabetes.py`.
   - Open your web browser and go to the provided local URL to interact with the diabetes prediction model.

## Deployment Requirements

- Python 3.x
- Jupyter Notebook
- scikit-learn
- pandas
- streamlit

Install dependencies using:

```bash
pip install -r requirements.txt
