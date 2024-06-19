# Human Activity Recognition Using Smartphone Data

Welcome to the Human Activity Recognition Using Smartphone Data project! This repository contains code and resources to classify different physical activities based on data collected from smartphone sensors.

<img src="https://drive.google.com/uc?export=view&id=1cph9CKKz1F3yfocaYz0KOFBJkUMzEVY_" alt="Human Activity Recognition Diagram">

## Overview
The goal of this project is to train a machine learning model that accurately classifies activities performed by volunteers wearing a smartphone (Samsung Galaxy S II) on the waist. The dataset includes 3-axial linear acceleration and 3-axial angular velocity captured at 50Hz. Activities include WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, and LAYING. Data has been randomly partitioned into 70% for training and 30% for testing.

## Data Pre-processing
The sensor signals (accelerometer and gyroscope) were pre-processed by:
- Applying noise filters
- Sampling in fixed-width sliding windows of 2.56 sec with 50% overlap (128 readings/window)
- Separating acceleration signals into body and gravity components using a Butterworth low-pass filter with 0.3 Hz cutoff frequency

## Exploratory Data Analysis (EDA)
EDA involves:
- Checking for duplicates and missing values
- Handling class imbalance
- Visualizing data distributions, correlations, and time series plots

## Model Training
Models utilized:
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Neural Network (NN)

### Logistic Regression
- Description of logistic regression model and its use in the project.

### Decision Tree
- Description of decision tree model and its use in the project.

### Random Forest
- Description of random forest model and its use in the project.

### Support Vector Machine (SVM)
- Description of SVM model and its use in the project.

### Neural Network (NN)
- Description of neural network model architecture and its use in the project.

## Usage
1. Clone the repository and navigate to the project directory.
2. Install dependencies listed in requirements.txt.
3. Execute Jupyter notebooks or Python scripts for data pre-processing, EDA, and model training.
