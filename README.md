# Fuel-Efficiency-Predictor
# Project Overview
This project aims to estimate the fuel efficiency of vehicles based on various input parameters. The project predicts accurate forecasts using machine learning algorithms, allowing customers to make informed decisions about vehicle performance and fuel usage.
## Table of Contents
1. Introduction
2. Dataset
3. Data pre-processing 
4. Building the model
5. Results
6. Conclusion
7. Technologies Used 
## Introduction
The Fuel Efficiency Predictor is a project aimed to estimate a vehicle's fuel consumption based on various parameters. With growing concerns about fuel efficiency and environmental impact, this project aims to provide a reliable and accessible solution for vehicle owners seeking to optimize their fuel usage.
## Dataset
The dataset used for this project is known as Auto-MPG dataset and is taken from https://archive.ics.uci.edu/dataset/9/auto+mpg. The dataset contains data of various vehicles such as 'MPG','Cylinders','Horsepower','Car Name','Acceleration','Origin','Model Year'.
## Data pre-processing:
Data preprocessing is a crucial step in ensuring the accuracy and effectiveness of the Fuel Efficiency Predictor. This phase involves preparing and cleaning the data to make it suitable for analysis and training of the model.
<br>
1)Data Cleaning:
<br>
(i)Handling Missing Values: Identified and addressed missing or incomplete data by removal, depending on the extent and importance of the missing values.
<br>
(ii)Removing Duplicates: Checked for and eliminated any duplicate records to maintain the integrity of the database.
<br>
2)Feature Engineering:
<br>
(i)Normalization/Standardization: Scaled numerical features to ensure uniformity and improve model performance. This helps in bringing different features to a common scale without distorting differences in the range of values.
<br>
(ii)Categorical Encoding: Converted categorical variables into numerical values using techniques such as one-hot encoding or label encoding to make them suitable for machine learning models.

## Building the model
1)Model Architecture:
<br>
(i)Input layer with 64 neurons and ReLU activation.
<br>
(ii)Hidden layer with 64 neurons and ReLU activation.
<br>
(iii)Output layer with a single neuron for predicting fuel efficiency.
<br>
(iv)Optimizer: RMSprop with a learning rate of 0.001.
<br>
(v)Loss Function: Mean Squared Error (MSE)
<br>
2)Training: The model is trained to minimize MSE using the provided dataset.
<br>
3)Evaluation: Training and validation performance are visualized with plots of Mean Absolute Error (MAE) and Mean Squared Error (MSE) over epochs.
