# Car Price Prediction Project

## Table of Contents
- [Project Overview](#project-overview)
- [Project Author](#project-author)
- [Data Loading and Preprocessing](#data-loading-and-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Encoding](#data-encoding)
- [Modeling](#modeling)
- [Evaluation and Visualization](#evaluation-and-visualization)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Usage](#usage)

## Project Overview
This project, titled "Car Price Prediction," is a data science project focused on predicting the selling prices of used cars. The project involves data loading, preprocessing, exploratory data analysis, data encoding, modeling, evaluation, and visualization.

## Project Author
- Author: Hassan Anwar

## Data Loading and Preprocessing
- Data was loaded from a CSV file containing information about cars, including features like car name, year, selling price, present price, driven kilometers, fuel type, selling type, transmission, and owner.
- Duplicate records were detected and removed from the dataset.

## Exploratory Data Analysis (EDA)
- EDA was conducted to visualize the correlation between numerical features and the distribution of selling prices.

## Data Encoding
- Categorical columns like 'Fuel_Type,' 'Selling_type,' and 'Transmission' were encoded into numerical values to prepare the data for modeling.

## Modeling
- Linear Regression and Random Forest Regressor models were used for predicting car prices.
- Model evaluation was performed using Mean Squared Error (MSE) and R-squared (R2).

## Evaluation and Visualization
- The performance of the models was evaluated, and predictions were visualized using scatter plots.
- Feature importances were calculated and visualized for the Random Forest model.

## Getting Started
To run this project locally, you can follow these steps:

## Dependencies
Make sure you have the following dependencies installed:
- Python
- Jupyter Notebook
- Required Python libraries (e.g., pandas, numpy, matplotlib, seaborn, scikit-learn)

## Usage
- Clone the project repository to your local machine.
- Open Jupyter Notebook and run the project's notebook to see the code and results.
- Modify or enhance the code as needed for your own analysis.
