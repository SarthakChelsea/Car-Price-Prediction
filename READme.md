# Car Price Prediction Project

This repository contains the code and documentation for a car price prediction project. In this project, we predict car prices using the Quikr car sales dataset from Kaggle. We have performed various steps, including data cleaning, data exploration, data preprocessing, and regression using the random forest algorithm. Additionally, we have created a data preprocessing and regression pipeline with hyperparameter tuning and deployed the model on Flask, achieving an R2 score of 0.768.

![image](https://drive.google.com/uc?export=view&id=1EpksVNQs1xAxofLiLe1OjlRQlOcyGA85)

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Data Cleaning](#data-cleaning)
- [Data Exploration](#data-exploration)
- [Data Preprocessing](#data-preprocessing)
- [Regression with Random Forest](#regression-with-random-forest)
- [Pipeline with Hyperparameter Tuning](#pipeline-with-hyperparameter-tuning)
- [Model Deployment with Flask](#model-deployment-with-flask)
- [Results](#results)
- [Contributing](#contributing)

## Project Overview

Car price prediction is a common problem in the automotive industry and can be valuable for both buyers and sellers. In this project, we aim to predict car prices based on various features provided in the Quikr car sales dataset. We have followed a structured approach to build a robust model for this prediction task.

## Dataset

We used the Quikr car sales dataset from Kaggle, which contains information about various car listings, including features like make, model, year, fuel type, mileage, and price. This dataset is used for training and evaluating our car price prediction model.

## Installation

To run this project, you'll need to have Python and several libraries installed. You can install the required libraries using `pip` with the provided `requirements.txt` file.

```bash
pip install -r requirements.txt
```

## Usage

Follow these steps to use this project:

1. Clone the repository:

```bash
git clone https://github.com/SarthakChelsea/car-price-prediction.git
cd car-price-prediction
```

2. Install the required dependencies (as mentioned in the Installation section).

3. Run the Flask application to deploy the model:

```bash
python application.py
```

4. Access the web application at `http://localhost:5000` in your web browser.

## Data Cleaning

We conducted data cleaning to handle missing values, remove duplicates, and ensure the dataset's quality and consistency. This step is essential to create a reliable predictive model.

## Data Exploration

Exploratory Data Analysis (EDA) was performed to gain insights into the dataset. Visualizations and statistical analyses were used to understand the relationships between features and the target variable (car prices).

## Data Preprocessing

Data preprocessing involved transforming and encoding categorical features, scaling numerical features, and splitting the data into training and testing sets.

## Regression with Random Forest

We used the Random Forest regression algorithm to build a predictive model for car prices. Random Forest is an ensemble learning method that combines multiple decision trees to make accurate predictions.

## Pipeline with Hyperparameter Tuning

To streamline the data preprocessing and modeling process, we created a pipeline that includes data preprocessing steps and hyperparameter tuning for the Random Forest algorithm using RandomizedSearchCV. This pipeline ensures consistency and repeatability of the model building process.

## Model Deployment with Flask

The trained model was deployed using Flask, creating a web application where users can input car information, and the application will predict the car's price based on the trained model.

## Results

Our model achieved an R2 score of 0.768, indicating its ability to explain the variance in car prices. This score suggests that the model is a valuable tool for predicting car prices based on the provided features.

## Contributing

Contributions to this project are welcome. If you have any ideas for improvements or would like to fix issues, please fork the repository and create a pull request.
