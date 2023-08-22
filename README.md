# Parkinson-Disease-Detection


This repository contains a Parkinson's Disease detection system implemented using Python and various machine learning libraries. The system aims to accurately classify individuals as either having Parkinson's Disease or being healthy based on certain features extracted from their voice recordings.



## Table of Contents

Introduction

Libraries Used

Data Preprocessing

Model Training

Evaluation

Usage

Contribution



## Introduction

Parkinson's Disease is a neurodegenerative disorder that affects movement control. Voice recordings have been shown to contain valuable information for detecting Parkinson's Disease. This project utilizes machine learning techniques to build a predictive model that can classify whether an individual has Parkinson's Disease or not.



## Libraries Used

The following Python libraries were used in this project:

Nmpy: For numerical computations and array operations.

Pandas: For data manipulation and analysis.

Seaborn: For data visualization and exploratory data analysis.

Matplotlib.pyplot: For creating various plots and visualizations.

Sklearn.model_selection: For splitting the dataset into training and testing sets.

Sklearn.preprocessing: For standardizing the feature data.

Sklearn.svm: For implementing the Support Vector Machine (SVM) classifier.

Sklearn.metrics: For evaluating the model's performance using an accuracy score.



## Data Preprocessing
Prior to training, the dataset is preprocessed to handle any missing values, outliers, or other anomalies that might affect the model's performance.



## Model Training
The Support Vector Machine (SVM) classifier is employed to train the model. The dataset is split into training and testing sets, and feature scaling is applied using standardization.



## Evaluation
The trained model's performance is evaluated using the accuracy score metric. This metric measures the percentage of correctly classified instances in the testing set.



## Usage
Clone this repository on your local machine.
Install the required libraries listed in the requirements.txt file.
Run the provided Python script, parkinsons_disease_detection.ipynb, using a Jupyter Notebook.
The script will preprocess the data, extract features, train the SVM model, and display the accuracy score.



## Contribution
Contributions to this project are welcome! If you have any suggestions, bug reports, or enhancements, please submit a pull request or open an issue.


