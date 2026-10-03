# Student Result Prediction using Machine Learning

## Project Overview

This project uses Machine Learning to predict whether a student will pass or fail based on academic and performance-related factors.

The project demonstrates the basic Machine Learning workflow, including data loading, data analysis, model training, prediction, and evaluation.

## Dataset

The dataset contains student-related attributes used to predict the final result.

### Features

- Attendance
- Study Hours
- Internal Marks
- Assignment Marks
- Previous Marks

### Target Variable

- Result — Pass / Fail

## Machine Learning Algorithm

The project uses:

**Logistic Regression**

Logistic Regression is a supervised Machine Learning classification algorithm used to predict a categorical outcome.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Process

1. Load the dataset
2. Explore the data
3. Check for missing values
4. Select features and target
5. Split the dataset into training and testing data
6. Train the Logistic Regression model
7. Make predictions
8. Evaluate the model

## Files in this Repository

- `Student-Result-Prediction-ML.ipynb` — Jupyter Notebook containing the complete Machine Learning implementation.
- `student_data.xlsx` — Dataset used for the project.

## Project Objective

The objective of this project is to demonstrate how a Machine Learning classification model can be trained to predict student results from academic performance data.

## Model Training

The dataset was divided into training and testing sets using an 80:20 split.

- Training data: 120 records
- Testing data: 30 records

The Logistic Regression model was trained using the training dataset and then used to predict student results for the testing dataset.

## Model Evaluation

The model performance was evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

## Prediction

The trained model can predict whether a student is likely to pass or fail based on:

- Attendance
- Study Hours
- Internal Marks
- Assignment Marks
- Previous Marks

## How to Run

1. Download or clone this repository.
2. Open `Student-Result-Prediction-ML.ipynb` in Jupyter Notebook or Google Colab.
3. Make sure `student_data.xlsx` is in the same directory as the notebook.
4. Run the notebook cells in order.

## Project Structure

```text
Student-Result-Prediction-using-ML/
│
├── Student-Result-Prediction-ML.ipynb
├── student_data.xlsx
└── README.md

## Future Improvements

- Try other classification algorithms.
- Compare the performance of different models.
- Improve the dataset with additional relevant features.
- Develop a simple user interface for making predictions.
