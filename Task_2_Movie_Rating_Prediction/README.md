## Movie Rating Prediction with Python
📌 Project Overview

This project focuses on building a machine learning regression model that predicts the IMDb movie rating based on key movie attributes such as genre, director, actors, release year, and duration.

By analyzing historical movie data, the model learns patterns that influence how movies are rated by audiences and critics. This project demonstrates real-world applications of data preprocessing, feature engineering, and machine learning pipelines using Python.

## Objectives

Analyze historical IMDb India movie data

Perform data cleaning and preprocessing

Encode categorical features effectively

Train a regression model to predict movie ratings

Evaluate model performance using standard metrics

Predict ratings for new/unseen movies

## Dataset

Source: Kaggle

Dataset Name: IMDb India Movies

Link: https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies

## Dataset Features Used:

Feature	   :   Description

Genre	      :   Movie genre(s)

Director	  :  Movie director

Actor 1	    : Lead actor

Actor 2	    : Supporting actor

Actor 3	    : Supporting actor

Year	      :   Year of release

Duration	  :   Movie duration (minutes)

Rating	    :   IMDb rating (Target Variable)

## Technologies Used

Programming Language: Python

Libraries:

Pandas

NumPy

Scikit-learn

Jupyter Notebook

## Project Workflow

Data Loading

Load IMDb India movie dataset

Data Cleaning

Remove missing target values

Convert Year and Duration to numeric format

Handle missing categorical values

Feature Engineering

One-Hot Encoding for categorical variables

Numeric feature passthrough

Model Building

Random Forest Regressor

Scikit-learn Pipeline & ColumnTransformer

## Model Evaluation

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

Prediction

Predict ratings for new movie data

## Machine Learning Model

Algorithm: Random Forest Regressor

Reason for Choice:

Handles non-linear relationships well

Robust to outliers

Performs well with mixed data types

## Evaluation Metrics

MAE (Mean Absolute Error) – Measures average prediction error

MSE (Mean Squared Error) – Penalizes larger errors

R² Score – Indicates model explanatory power

## Sample Prediction
Input:
Genre: Drama
Director: Unknown
Actors: Unknown
Year: 2022
Duration: 120 minutes

Predicted IMDb Rating: 6.8 (example)

## 📁 Project Structure
Movie-Rating-Prediction/

├── IMDb_India_Movies.csv

├── movie_rating_prediction.ipynb

├── README.md

## How to Run the Project

Clone this repository

Download the dataset from Kaggle

Place IMDb_India_Movies.csv in the project directory

Open movie_rating_prediction.ipynb

Run all cells sequentially

 ## Conclusion

This project demonstrates how machine learning can be applied to predict movie ratings using structured metadata. It highlights the importance of data preprocessing, feature encoding, and model pipelines in building robust predictive systems.
