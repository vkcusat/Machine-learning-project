# House Price Prediction Using Linear Regression

## Project Overview
This project implements a Machine Learning model to predict house prices based on property features using Python and Scikit-learn.

The project demonstrates the complete basic workflow of a supervised machine learning regression problem, from data exploration to model evaluation.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## Dataset Description

The dataset contains 10 house records with the following features:

| Feature | Description |
|---|---|
| area | Area of the house |
| Bedrooms | Number of bedrooms |
| Age_year | Age of the property in years |
| price | House price (target variable) |

## Project Workflow

1. Import required libraries.
2. Load and explore the dataset.
3. Perform data quality checks.
4. Visualize the relationship between area and price.
5. Separate independent and dependent variables.
6. Split the dataset into training and testing sets (80:20).
7. Train a Linear Regression model.
8. Generate predictions.
9. Evaluate model performance.
10. Visualize actual vs predicted prices.

## Model Evaluation

The model is evaluated using the following metrics:

- **Mean Absolute Error (MAE):** Measures average absolute prediction error.
- **Mean Squared Error (MSE):** Measures average squared prediction error.
- **R² Score:** Measures how well the model explains the variation in house prices.

## Visualizations

- Area vs Price scatter plot
- Actual vs Predicted House Prices

## How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/vkcusat/Machine-learning-project.git
   ```

2. Install the required libraries:

   ```bash
   pip install pandas matplotlib scikit-learn
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `machine_learning_project.ipynb` and run all cells.

## Learning Outcomes

- Understanding supervised machine learning.
- Implementing Linear Regression using Scikit-learn.
- Performing exploratory data analysis.
- Evaluating regression models using performance metrics.
- Visualizing model predictions.

## Future Improvements

- Increase dataset size using real-world housing data.
- Perform feature engineering.
- Compare multiple regression algorithms.
- Apply cross-validation.
- Tune model hyperparameters.

## Author

**Vikash Kumar**

GitHub: [@vkcusat](https://github.com/vkcusat)
