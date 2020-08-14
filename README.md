# Heart Disease Prediction
Combination of machine learning classification models to predict whether a person has a heart disease

## Table of contents
* [Description](#description)
* [Methodologies](#methodologies)
* [Results](#results)
* [Files](#files)
* [Technologies](#technologies)
* [Packages](#packages)
* [Setup](#setup)
* [Usage](#usage)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## Description
The objective of this project is to predict 

Data source: framingham_heart_disease.csv - [Kaggle](https://www.kaggle.com/dileep070/heart-disease-prediction-using-logistic-regression)

## Methodologies
This project was created as the capstone assignment for Applied Machine Learning course at UT Dallas, including 2 projects:

Project 1 has 2 parts:
* **Part 1**: [Regression Task - Bike Rental Prediction](https://github.com/mypham14/bike-rental-prediction/blob/master/Project%201.ipynb): data cleaning, supervised machine learning regression models
* **Part 2**: [Classification Task - Heart Disease Prediction](https://github.com/mypham14/heart-disease-prediction/blob/master/Project%201.ipynb): data cleaning, supervised machine learning classification models
  - a mix of classification models *(ensemble learning, classification machine learning, principal component analysis and deep learning)* to provide hospitals a filtering system that helps patients identify and prevent potential predictors of having a heart disease 
  - Perform data cleansing and exploratory data analysis
     
Project 2 has 2 parts:
* **Part 1**: [Regression Task - Bike Rental Prediction](https://github.com/mypham14/bike-rental-prediction/blob/master/Project2_Regression.ipynb): ensemble learning, principal component analysis (PCA), regression models using PCA, deep learning (DL) models using neural networks
* **Part 2**: [Classification Task - Heart Disease Prediction](https://github.com/mypham14/heart-disease-prediction/blob/master/Project2_Classification.ipynb): ensemble learning, principal component analysis (PCA), classification models using PCA, deep learning (DL) models using neural networks
   - Apply a combination of models including Emsemble Learning (voting classifiers, bagging, pasting, adaboost and gradient boosting), Principal Component Analysis, Classification Machine Learning (KNN, Logistic Regression, Linear Support Vector Machine, Kernelilzed Support Vector Machine (rbf, poly, and linear), Decision Tree) and Deep Learning to predict whether a patient has a heart disease
   - Create Tableau dashboards for data analysis and visualization 
   - Automate the modeling process and deploy the chosen model into production in Azure ML

## Results
* **Model Result**: ARIMA time series provided the highest accuracy with a MSE of 0.22 (followed by KNN).
* **Visualization**: Tableau dashboards for the stock portfolio analysis were created [here]().
* **Automated ML and Deployment**: the chosen model (time series) was applied in Azure ML and deployed into production [here]().

## Files
* 
For all models, Close price is the predicted value.
* requirements.txt: text file containing all Python libraries used in the project

## Technologies
Project is created with:
* MS Excel
* SQL
* MySQL Server
* Anaconda
* Jupyter Lab
* Jupyter Notebook
* Google Colab
* Python 3
* R Studio
* Tableau
* Azure ML Studio
* Windows

## Packages
* pandas
* numpy
* matplotlib
* seaborn
* tensorflow
* keras
* beautifulsoup
* requests
* scikit-learn
* statsmodels.tsa
* mysql.connector

## Setup
* Download all data files
* Install the requirements using `pip install -r requirements.txt`.
  - Make sure you use Python 3

## Usage
* Run `Stock Price Prediction.ipynb` to see all project steps

## Status
Project is finished.

## Inspiration
Project inspired by [Analytics Vidhya](analyticsvidhya.com/)'s tutorials of prediction models.

## Contact
Created by [@mypham14](https://github.com/mypham14/) - feel free to contact me on my [LinkedIn](https://www.linkedin.com/in/mytrapham)!
