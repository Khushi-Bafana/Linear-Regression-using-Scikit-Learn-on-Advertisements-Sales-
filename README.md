
# 🚀 Linear Regression using Scikit-Learn

## Overview
This Jupyter Notebook demonstrates the implementation of Linear Regression using Scikit-Learn. The project utilizes the Advertising Budget and Sales dataset to analyze the relationship between advertising expenditures across different media channels and the corresponding sales figures. The notebook covers essential steps including data preprocessing, model training, evaluation, and visualization, ensuring a hands-on learning experience for both beginners and experts.

## Features
- Data Preprocessing: Handle missing values, select features, and prepare the dataset for training.
- Model Training: Implement and train a linear regression model using Scikit-Learn.
- Performance Evaluation: Assess model accuracy using Mean Squared Error (MSE) and R-squared (R²) metrics.
- Data Visualization: Generate regression plots, residual plots, and error distributions for better insights.

## Prerequisites
Before running the notebook, ensure you have the following dependencies installed:

- Python (>=3.7)
- Jupyter Notebook
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

Install the required libraries using:
```bash
pip install scikit-learn pandas numpy matplotlib seaborn
```

## Getting Started
1. Clone or download this repository.
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook "Linear Regression using Scikit-Learn.ipynb"
   ```
3. Execute the cells sequentially to run the complete workflow.
4. Modify parameters or use different datasets to experiment with linear regression techniques.

## Dataset Information
The dataset used in this project is Advertising Budget and Sales.csv, which contains information on advertising expenditures across multiple media channels and corresponding sales figures. 

Columns in the dataset:
- TV: Advertising budget spent on TV marketing.
- Radio: Advertising budget spent on radio marketing.
- Newspaper: Advertising budget spent on newspaper marketing.
- Sales: Sales figures corresponding to the advertising expenditure.

Ensure the dataset is present in the working directory before running the notebook.

## Model Evaluation Metrics
- Mean Squared Error (MSE): Measures the average squared difference between actual and predicted sales.
- R-squared (R²) Score: Evaluates how well advertising expenditures explain the variance in sales.

## Visualizing Results
- Scatter Plots: Show the relationship between advertising budgets and sales.
- Regression Line: Illustrates the best-fit line for predictions.
- Residual Plots: Assess the distribution of errors to check model assumptions.

