# Big_Data_Spark

# Description 
This project demonstrates the use of Apache Spark for Big Data Machine Learning. We implement a classification model to predict heart disease using the Heart Disease UCI dataset. The project explores Spark ML Pipelines and compares different processing techniques.

#Dataset
The Heart Disease UCI dataset contains medical records of patients, with various health-related features such as age, cholesterol level, blood pressure, and chest pain type. The goal is to predict the presence of heart disease based on these features.
Objective of the Project
We will build a Machine Learning pipeline using Apache Spark to:
- Preprocess the data (handle missing values, encode categorical variables)
- Train a classification model (e.g., Random Forest)
- Evaluate performance using accuracy, F1-score, and ROC AUC
- Optimize the model by addressing class imbalance

This project showcases Big Data ML processing using Spark for scalable and efficient predictions. 

# Prerequisites
Before running this project,  you should have:

Apache Spark installed
Python 3
Google Colab (for cloud execution)
The dataset: HeartDiseaseUCI.csv

# Project Structure
/
|-- spark_project.ipynb  #Notebook
|-- HeartDiseaseUCI.csv  #Dataset
|-- README.md  #Documentation

# Steps 
- Install and configure Apache Spark on Google Colab.

- Load the dataset and perform preprocessing: Handle missing values, Convert categorical features using StringIndexer, Assemble features using VectorAssembler.

- Train a classification model using RandomForestClassifier.

- Evaluate the model with MultiClassification.

- Optimize the model by handling class imbalance and tune hyperparameters
  
- Make predictions

# Execution
You can see the notebook

# Author
Ismael KOULIBALY










