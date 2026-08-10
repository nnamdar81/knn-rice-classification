# knn-rice-classification
Rice classification using a KNN algorithm implemented from scratch with data cleaning, standardization, Euclidean distance, and majority voting.

# KNN Rice Classification

A data-mining project for classifying rice samples using a **K-Nearest Neighbors (KNN) algorithm implemented from scratch**.

## Project requirements

The assignment asks for:

- Importing the CSV dataset with pandas.
- Exploratory Data Analysis:
  - inspect column data types,
  - print the first and last 10 rows,
  - report the dataset dimensions,
  - calculate the minimum and maximum of each feature.
- Data cleaning:
  - detect normal missing values and values represented by `???`,
  - handle duplicate rows.
- Data normalization:
  - calculate the mean and standard deviation of each feature,
  - standardize each feature to mean 0 and standard deviation 1.
- KNN processing:
  - receive a new sample,
  - normalize it using the original dataset statistics,
  - calculate Euclidean distances,
  - select the `k` nearest samples,
  - predict the class using majority voting.

