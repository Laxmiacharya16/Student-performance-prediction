# Student-performance-prediction

# Student Performance Predictions

This project aims to predict student performance (test scores) based on various factors such as Gender, Ethnicity, Parental level of education, Lunch, and Test preparation course.

## Problem Statement

The project addresses how student performance is influenced by different variables.

## Data Collection

The dataset used for this project can be found [here](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977). It consists of 8 columns and 1000 rows.

## Exploratory Data Analysis (EDA)

The notebook contains detailed exploratory data analysis, including data overview, missing values, duplicates, statistics, and insights derived from visualization.

## Insights

- Female students tend to perform better than male students.
- Standard lunch correlates with better exam performance.
- Parental education levels show varying impacts on student performance.
- Group A and Group B students tend to perform poorly.
- Most students score between 60-80 in Maths and 50-80 in Reading and Writing.

## Machine Learning (Model Building)

The notebook includes model building using various regression algorithms like Linear Regression, Ridge Regression, Lasso Regression, K Neighbors Regressor, Decision Tree Regressor, Random Forest Regressor, XGBoost Regressor, CatBoost Regressor, and AdaBoost Regressor. Ridge Regression produced the best results.

## Getting Started

To run the notebook:

1. Clone the repository.
2. Open the notebook in Google Colab or Jupyter Notebook.

## Requirements

- Python 3.x
- Jupyter Notebook or Google Colab
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, catboost, xgboost

## License

This project is licensed under the [MIT License](LICENSE)
