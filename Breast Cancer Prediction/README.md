# Breast Cancer Prediction

This project demonstrates breast cancer prediction using Logistic Regression (LR) based on the `load_breast_cancer` dataset provided by the scikit-learn library.

## Dataset

The `load_breast_cancer` dataset is a built-in breast cancer diagnostic dataset in scikit-learn. It contains a total of 569 instances with 30 numeric features. 
The features include various measurements such as mean radius, mean texture, mean perimeter, mean area, mean smoothness, mean compactness, mean concavity, mean symmetry, and mean fractal dimension.

## Usage

To predict breast cancer using the `load_breast_cancer` dataset, follow these steps:

1. Open the `breast_cancer_prediction.py` script in a Python IDE or text editor.
2. Run the script to execute the code.

The script performs the following steps:

1. Loads the breast cancer dataset using `sklearn.datasets.load_breast_cancer()`.
2. Splits the dataset into training and testing sets.
3. Trains a logistic regression model on the training data.
4. Makes predictions on the test data using the trained model.
5. Calculates the accuracy of the model.

## Results

The accuracy of the breast cancer prediction model on the test set is 96% reported at the end of the script execution. 
This accuracy score provides an indication of how well the model performs in classifying breast cancer cases.
