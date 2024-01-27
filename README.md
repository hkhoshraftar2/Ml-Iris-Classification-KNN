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
git clone https://github.com/hkhoshraftar2/Ml-Iris-Classification-KNN.git
cd Ml-Iris-Classification-KNN
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

# یادگیری ماشین با Scikit-Learn و مجموعه داده Iris

## مرور
این مخزن شامل یک اسکریپت پایتون است که از کتابخانه Scikit-Learn برای وظایف یادگیری ماشین استفاده می‌کند. این اسکریپت به مجموعه داده معروف Iris متمرکز است که یک مجموعه داده گسترده در یادگیری ماشین است. هدف این است که نشان دهد چگونه یک مدل یادگیری ماشین را با استفاده از Scikit-Learn آموزش داده و از آن برای پیش‌بینی نوع صحیح گل آی‌ریس بر اساس ویژگی‌های ورودی استفاده شود.

## محتوا
- `iris_ml.py`: اسکریپت پایتون که وظایف زیر را انجام می‌دهد:
  - مجموعه داده Iris را از Scikit-Learn بارگذاری می‌کند.
  - مجموعه داده را به مجموعه‌های آموزش و آزمون تقسیم می‌کند.
  - یک مدل یادگیری ماشین با استفاده از یک طبقه‌بند از Scikit-Learn ایجاد می‌کند.
  - مدل را بر روی مجموعه آموزش آموزش می‌دهد.
  - مدل را بر روی مجموعه آزمون تست می‌کند.
  - به کاربر این امکان را می‌دهد که مقادیر ویژگی جدید را وارد کرده و نوع گل آی‌ریس را پیش‌بینی کند.

## نیازمندی‌ها
اطمینان حاصل کنید که نیازمندی‌های زیر نصب شده باشند:

```bash
pip install scikit-learn
pip install pandas
pip install numpy
```

## راهنمای استفاده
1. این مخزن را کلون کنید:

```bash
git clone https://github.com/hkhoshraftar2/Ml-Iris-Classification-KNN.git
cd Ml-Iris-Classification-KNN
```

2. اسکریپت پایتون را اجرا کنید:

```bash
python ml.py
```

3. دستورات روی صفحه را دنبال کرده و مدل را آموزش دهید، آزمایش کنید و مقادیر جدید برای پیش‌بینی وارد کنید.

## نمونه
```python
# مثال برای ورودی پیش‌بینی
new_values = [[5.1, 3.5, 1.4, 0.2]]

# استفاده از مدل آموزش دیده برای پیش‌بینی
predicted_class = model.predict(new_values)

print(f"نوع گل آی‌ریس پیش‌بینی شده: {predicted_class[0]}")
```

