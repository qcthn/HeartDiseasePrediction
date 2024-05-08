
# Data Mining Project: Heart Disease Prediction

![Heart Disease](https://images.unsplash.com/photo-1506084868230-9b2cfab6751b)

## Overview

This project focuses on predicting the likelihood of heart disease based on various health factors using machine learning techniques. The dataset used for analysis contains information on individuals' health attributes such as BMI, smoking habits, alcohol consumption, and more.

## Project Structure

- **Source Code**: The source code for the project is available in the Jupyter Notebook file named `Chuandoanbenhtim-DataMining.ipynb`.

## Data Exploration and Preprocessing

The project begins with exploratory data analysis to understand the dataset's characteristics and preprocess the data appropriately. Key steps include:

- Importing necessary libraries
- Checking data integrity and completeness
- Visualizing data relationships using heatmaps and count plots
- Preprocessing data by handling missing values and encoding categorical variables

## Feature Selection and Ranking

Feature selection is performed to identify the most relevant attributes for predicting heart disease. Techniques such as Extra Trees Classifier and SelectKBest are employed to rank features based on their importance.

## Principal Component Analysis (PCA)

Principal Component Analysis is utilized to reduce the dimensionality of the dataset while preserving important information. This technique helps in visualizing the data in a lower-dimensional space.

## Model Training and Evaluation

Several machine learning algorithms are trained and evaluated to predict heart disease:

- Logistic Regression
- Decision Tree Classification
- XGBoost Classification
- Adaboost Classification
- K Nearest Neighbour Classification
- Support Vector Machine Classification
- Random Forest Classification

The accuracy and performance of each model are assessed using metrics such as accuracy score, confusion matrix, and classification report.

## Graphical User Interface (GUI)

A graphical user interface (GUI) is implemented to provide an interactive platform for users to input their health attributes and obtain predictions regarding their risk of heart disease. This GUI facilitates easy access and usage of the predictive model.

## Dependencies

- Python 3
- Jupyter Notebook
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, imbalanced-learn, plotly, gradio

## Usage

To run the project, ensure that Python and the required libraries are installed on your system. Execute the Jupyter Notebook `Chuandoanbenhtim-DataMining.ipynb` to explore the code and perform analysis.

For using the GUI, install the `gradio` library and run the provided interface.

---

Feel free to customize the README further based on additional details or specific instructions related to your project.
