# Reels Scrolling vs Eyesight — Linear Regression

## Project Overview

This project uses Linear Regression to study the relationship between reels scrolling per hour and an eyesight score using a small practice dataset.

The project demonstrates the basic workflow of a Machine Learning regression problem, from loading the dataset to training the model and making predictions.

> Note: The dataset is synthetic and created only for Machine Learning practice. It is not intended for medical or clinical conclusions.

## Dataset

The dataset contains two main columns:

* `Reels_Scroll_Per_Hour` — Number of reels scrolled per hour
* `Eye_Sight_Score` — Practice eyesight score from 10 to 100

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Machine Learning Workflow

1. Loaded the CSV dataset
2. Explored the data
3. Calculated mean values
4. Selected independent and dependent variables
5. Split data into training and testing sets
6. Created a Linear Regression model
7. Trained the model
8. Generated predictions
9. Evaluated the model using:

   * MAE
   * MSE
   * RMSE
   * R² Score
10. Visualized the regression line
11. Predicted the score for new input values

## Model

The Linear Regression model follows:

`y = mx + c`

Where:

* `y` = predicted eyesight score
* `x` = reels scrolling per hour
* `m` = slope
* `c` = intercept

## Model Evaluation

The model achieved an R² score of approximately:

**0.997**

This score reflects the model's performance on this synthetic practice dataset.

## Files

* `reels_eyesight.csv` — Dataset
* `linear_regression_reels_eyesight.ipynb` — Jupyter Notebook
* `README.md` — Project documentation

## Learning Outcome

Through this project, I practiced the complete basic Linear Regression workflow, including data preparation, train-test splitting, model training, prediction, evaluation, and visualization.
