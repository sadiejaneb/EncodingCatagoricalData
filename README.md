# EncodingCatagoricalData
EncodingCatagoricalData-Titanic Data

# Titanic Dataset Preprocessing

## Overview
This project is focused on preprocessing the Titanic dataset, a well-known dataset used in data science and machine learning. The goal is to prepare the data for a machine learning model that predicts whether a passenger survived based on features like age, gender, ticket class, etc.

## Features
- Load and explore the Titanic dataset.
- Handle categorical data using OneHotEncoder and LabelEncoder.
- Transform features into a suitable format for feeding into machine learning models.

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn

## Installation
Ensure that you have Python installed on your machine. You can install the required packages using pip:

```bash
pip install pandas numpy scikit-learn
```

If you are using Anaconda, use the following:

```bash
conda install pandas numpy scikit-learn
```

## Usage

1. Load the dataset using pandas.
2. Preprocess the data:
   - Use `ColumnTransformer` and `OneHotEncoder` to encode categorical features.
   - Use `LabelEncoder` to encode binary categorical data.
   - Split the dataset into features (`X`) and the target variable (`y`).

## License

Distributed under the MIT License. See `LICENSE` for more information.
