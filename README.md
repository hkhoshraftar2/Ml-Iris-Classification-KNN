# Machine Learning with Scikit-Learn and Iris Dataset

## Overview

This repository contains a Python script that utilizes the Scikit-Learn library for machine learning tasks. The script focuses on the famous Iris dataset, a widely used dataset in machine learning. The goal is to demonstrate how to train a machine learning model using Scikit-Learn and use it to predict the correct type of iris flower based on input features.

## Contents

- `iris_ml.py`: Python script that performs the following tasks:
  - Loads the Iris dataset from Scikit-Learn.
  - Divides the dataset into training and testing sets.
  - Builds a machine learning model using a classifier from Scikit-Learn.
  - Trains the model on the training set.
  - Tests the model on the testing set.
  - Allows the user to input new feature values and predicts the iris flower type.

## Requirements

Make sure you have the following dependencies installed:

```bash
pip install scikit-learn
pip install pandas
pip install numpy
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/your-username/iris-ml.git
cd iris-ml
```

2. Run the Python script:

```bash
python ml.py
```

3. Follow the on-screen instructions to train the model, test it, and input new values for prediction.

## Example

```python
# Example input for prediction
new_values = [[5.1, 3.5, 1.4, 0.2]]

# Use the trained model for prediction
predicted_class = model.predict(new_values)

print(f"Predicted Iris Flower Type: {predicted_class[0]}")
```

Feel free to explore and modify the script to suit your specific needs. Happy coding!
