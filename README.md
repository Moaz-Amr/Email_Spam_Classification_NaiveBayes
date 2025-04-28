# Email Spam Classification using Multinomial Naive Bayes

## Short Description

This project classifies emails as spam (1) or not spam (0) based on word counts using the `emails.csv` dataset. It utilizes a Multinomial Naive Bayes classifier.

## Project Overview

The notebook `day7/Moaz_(task3).ipynb` performs the following:

1.  **Load Data:** Loads the email dataset (`emails.csv`), where features likely represent word frequencies or presence.
2.  **Feature/Target Split:** Separates the features (columns 1 to 3000) from the target variable (column 3001).
3.  **Train-Test Split:** Splits the data into training and testing sets.
4.  **Model Training:** Trains a `MultinomialNB` model from `sklearn.naive_bayes`.
5.  **Evaluation:**
    *   Predicts labels for the test set.
    *   Calculates the accuracy score.
    *   Generates and plots a confusion matrix using Seaborn.

## Dataset

*   **emails.csv:** Contains features representing word occurrences in emails and a target column indicating if the email is spam.

## Model Used

*   **Multinomial Naive Bayes:** A probabilistic classifier suitable for classification with discrete features (like word counts).

## Requirements

*   Python 3
*   NumPy
*   Pandas
*   Scikit-learn
*   Matplotlib
*   Seaborn

## How to Run

1.  Ensure you have the required libraries installed (`pip install numpy pandas scikit-learn matplotlib seaborn`).
2.  Make sure the `emails.csv` file is in the correct path relative to the notebook.
3.  Run the Jupyter Notebook `day7/Moaz_(task3).ipynb`.
