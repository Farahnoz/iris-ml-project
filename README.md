# Iris Flower Classification

This project uses a Random Forest classifier to classify iris flowers into three species: Setosa, Versicolor, and Virginica based on their features.

## Project Overview

- **Data Loading and Exploration:** Load and explore the Iris dataset.
- **Data Preprocessing:** Preprocess the data by separating features and target variable, splitting the dataset, and standardizing the features.
- **Model Training:** Train a Random Forest classifier.
- **Model Evaluation:** Evaluate the model using confusion matrix, classification report, and accuracy score.
- **Model Deployment:** Save the trained model for future use.

## Files

- `iris-ml-project.ipynb`: The Jupyter notebook containing the data analysis and model training.
- `iris_classifier.joblib`: The saved Random Forest model.
- `README.md`: Project documentation.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/iris-ml-project.git
   cd iris-ml-project
mv /

Install the required libraries:
pip install pandas seaborn matplotlib scikit-learn joblib

Run the notebook:
jupyter notebook iris-ml-project.ipynb

Insights
Model Performance: The Random Forest classifier achieved a high accuracy score, indicating that it is effective in classifying iris flowers.
Feature Importance: Petal length and petal width were the most important features for classification.

License
This project is licensed under the MIT License - see the LICENSE file for details.