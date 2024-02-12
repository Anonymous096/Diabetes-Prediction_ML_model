# Diabetes Prediction Machine Learning Model

## Introduction
This repository contains a machine learning model for predicting diabetes based on certain features. The model is built using Python and utilizes various libraries for data manipulation, visualization, and modeling. Three algorithms, namely Decision Tree, Logistic Regression, and Random Forest, are implemented to predict the likelihood of diabetes occurrence.

## Libraries Used
- **NumPy**: For numerical computations and array manipulation.
- **Matplotlib**: For data visualization and plotting graphs.
- **Pandas**: For data manipulation and analysis.
- **Seaborn**: For statistical data visualization.

## Dataset
The model is trained and tested on a dataset containing features related to diabetes diagnosis. The dataset used can be found in [Kaggle Diabetes Dataset](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset) and is preprocessed to handle missing values and normalize the features.

## Algorithms
### Decision Tree
Decision Tree algorithm is a non-parametric supervised learning method used for classification tasks. It creates a model that predicts the value of a target variable by learning simple decision rules inferred from the data features.

### Logistic Regression
Logistic Regression is a statistical method for analyzing a dataset in which there are one or more independent variables that determine an outcome. It is used for binary classification problems and estimates the probability that a given instance belongs to a particular class.

### Random Forest
Random Forest is an ensemble learning method used for classification and regression tasks. It constructs a multitude of decision trees during training and outputs the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees.

## Usage
To run the model:
1. Ensure you have Python installed on your system.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the main script `diabetes_prediction.py` to train and test the model.

## Results
The accuracy of the model using each algorithm is measured and compared to evaluate their performance. The results are visualized using appropriate plots to provide insights into the model's effectiveness in predicting diabetes occurrence.

## Contributors
- [Saksham Sharma](https://github.com/Anonymous096)

## License
This project is licensed under the [MIT License](link to license).
