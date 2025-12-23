Task 1: Exploring and Visualizing Iris Dataset

Objective:
To load, inspect, and visualize the Iris dataset.

Tools used:
- Python
- pandas
- matplotlib
- seaborn

Steps:
1. Loaded dataset using seaborn
2. Inspected shape and columns
3. Used info() and describe()
4. Created scatter plots, histograms, and box plots

Task 2: Short-Term Stock Price Prediction

Objective:
To predict the next day's closing stock price using historical data.

Dataset:
Stock data retrieved from Yahoo Finance using yfinance.

Model Used:
Linear Regression

Features:
- Open
- High
- Low
- Volume

Target:
- Next day Close price

Result:
The model predicts future closing prices and compares them with actual values using a line plot.

Task3:
# Heart Disease Prediction using Machine Learning

## Overview
This project predicts whether a person is at risk of heart disease using medical data from the Heart Disease UCI dataset. A machine learning classification model is trained to analyze health attributes and make predictions.

The goal of this project is to demonstrate binary classification, medical data analysis, and model evaluation techniques using Python.

---

## Dataset
- **Name:** Heart Disease UCI Dataset  
- **Source:** Kaggle  
- **Target Variable:**  
  - `target = 1` → Heart disease present  
  - `target = 0` → No heart disease  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Project Workflow
1. Data loading and inspection  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature scaling  
5. Model training (Logistic Regression)  
6. Model evaluation using:
   - Accuracy
   - Confusion Matrix
   - ROC Curve and AUC
7. Feature importance analysis  

---

## Model Evaluation
- **Accuracy:** Evaluated on test data  
- **ROC-AUC:** Measures model’s ability to distinguish between classes  
- **Confusion Matrix:** Shows correct and incorrect predictions  

---

## Key Features Affecting Prediction
- Chest pain type (`cp`)
- Maximum heart rate achieved (`thalach`)
- ST depression (`oldpeak`)
- Exercise induced angina (`exang`)
- Number of major vessels (`ca`)

4.General Health Query Chatbot

Prompt Engineering Based

Project Description

This project implements a simple General Health Query Chatbot using a Large Language Model (LLM). The chatbot is designed to answer general health-related questions in a friendly and easy-to-understand manner while strictly avoiding medical diagnosis or harmful advice.

The main focus of this project is prompt engineering, safe response handling, and building a basic conversational AI system.

Objective

To build a chatbot that answers general health questions

To use prompt engineering to control AI behavior

To apply safety filters to avoid harmful medical advice

To demonstrate basic usage of LLMs through Python

Tools and Technologies

Python

Google Colab

Hugging Face Transformers

Mistral-7B-Instruct (Open-source LLM)

Key Features

Answers common health-related questions

Friendly and clear responses

Safety filter to block medical diagnosis or dosage advice

Prompt-controlled AI behavior

Fully runs on Google Colab without paid APIs

Prompt Engineering Strategy

The chatbot uses a structured prompt that instructs the model to:

Act like a helpful medical assistant

Provide only general health information

Avoid diagnosis, prescriptions, or treatment advice

Encourage consulting healthcare professionals when needed

This ensures safe and responsible AI interaction.

Safety Handling

The chatbot checks user queries for sensitive keywords such as:

diagnosis

dosage

treatment

prescription

If such terms are detected, the chatbot responds with a safe message advising the user to consult a qualified healthcare professional.

Example Queries

What causes a sore throat?

Is paracetamol safe for children?

How can I stay healthy during flu season?
---

## How to Run the Project
1. Clone the repository
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
