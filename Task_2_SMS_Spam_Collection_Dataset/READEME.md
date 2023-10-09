# SMS Spam Classification Project

## Introduction

This project is aimed at building a machine learning model to classify SMS messages as either "spam" or "ham" (non-spam). It uses the SMS Spam Collection Dataset, which contains labeled SMS messages.

## Project Overview

- **Data Loading and Preprocessing**:
  - The dataset is loaded using Pandas, unnecessary columns are removed, and column names are renamed.
  - Missing values are checked and duplicates are removed to ensure clean data.

- **Exploratory Data Analysis (EDA)**:
  - The dataset is explored, including data types and category distribution.
  - Word clouds are generated to visualize the most common words in spam and ham messages.

- **Label Encoding**:
  - The "Category" column is encoded into numerical labels (0 for "ham" and 1 for "spam").

- **Train-Test Split**:
  - Data is split into training and testing sets for model evaluation.

- **Feature Extraction (Count Vectorization)**:
  - Text messages are converted into numerical features using CountVectorizer.

- **Model Training**:
  - A Multinomial Naive Bayes model is trained on the training data.

- **Pipeline**:
  - A pipeline is created to streamline the data preprocessing and modeling steps.

- **Model Evaluation**:
  - The model's accuracy is evaluated on the test data.
  - Predictions are made for sample emails.

- **Confusion Matrix Visualization**:
  - A confusion matrix is created and visualized to assess the model's performance.

## Prerequisites

To run this project, you'll need the following libraries installed:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Wordcloud

You can install these libraries using `pip` or `conda`.

## Usage

1. **Data Preparation**:
   - Ensure you have the SMS Spam Collection Dataset in the specified location (or update the data file path in the code).

2. **Code Execution**:
   - Run the Python script to execute the project steps. Make sure to follow the code comments for guidance.

3. **Interpret Results**:
   - Examine the results, including model accuracy, confusion matrix, and word clouds.

## Example Outputs

- Sample word clouds showing common words in spam and ham messages.
- Confusion matrix heatmap visualizing model performance.

## Contributing

Contributions are welcome! If you have suggestions, enhancements, or bug fixes, please open an issue or submit a pull request.

## Author

Hassan Anwar


## Acknowledgments

- SMS Spam Collection Dataset: [Link](https://www.kaggle.com/uciml/sms-spam-collection-dataset)

## Contact Information

For inquiries or feedback, please contact Hassan Anwar at code211944@gmail.com.
