# Student Placement Prediction

This project contains a Jupyter notebook (`test.ipynb`) that builds and evaluates a machine learning model to predict student placements based on their CGPA and IQ.

## Description

The notebook performs the following steps:
1.  Loads a dataset from `placement.csv`.
2.  Cleans and prepares the data for modeling.
3.  Visualizes the data to understand the relationship between features and the target variable.
4.  Splits the data into training and testing sets.
5.  Scales the features using `StandardScaler`.
6.  Trains a Logistic Regression model.
7.  Evaluates the model's performance.
8.  Visualizes the decision boundary of the trained model.
9.  Saves the trained model to a file named `model.pkl`.

## Dependencies

To run this notebook, you will need the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `mlxtend`

You can install these dependencies using pip:
```bash
pip install numpy pandas matplotlib scikit-learn mlxtend
```

## Usage

1.  **Provide the dataset:** This repository does not include the `placement.csv` file. You need to provide this file in the same directory as the notebook. The CSV file should have the following columns: `cgpa`, `iq`, and `placement`.
2.  **Run the notebook:** Open and run the `test.ipynb` notebook in a Jupyter environment.

## Model

The project uses a Logistic Regression model from `scikit-learn` to predict student placements. The model achieves an accuracy of 100% on the test set.

## Output

After running the notebook, a file named `model.pkl` will be created in the same directory. This file contains the trained Logistic Regression model and can be used for future predictions.
