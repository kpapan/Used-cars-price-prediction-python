# Implementing Machine Learning Techniques on a Used Cars Dataset Using Python

In this project, I utilized the same dataset as the one used in the study "Application of Machine Learning Algorithms for Predicting Prices in the Used Car Market" (R programming language). However, this project, implemented in Python, includes unique elements and enhancements.

## Key Components

- **Data Preprocessing**
  - Handling Missing Values (NA): Address missing values in the dataset.
  - Handling Outliers: Detect and manage outliers in the data.
  - Feature Engineering: Extract and create meaningful features.
  - Currency Conversion: Convert prices from Polish Zloty to Euros.
  - Feature Extraction and Transformation: Extract relevant features and transform them into suitable formats.
  - Categorical Feature Transformation: Normalize and encode categorical variables.
  - Numerical Variable Transformations: Apply transformations to numerical variables to improve model performance.

- **Principal Component Analysis (PCA)**
  - Used PCA for feature selection.

- **K-Means Clustering**
  - Applied K-Means clustering to identify clusters of similar cars.

- **Support Vector Machine (SVM)**
  - Built an SVM model to classify each new entry into one of the pre-specified clusters.
  - Evaluated the SVM model using ROC curve, AUC, and accuracy metrics.

- **Random Forests Regression**
  - Developed a Random Forests Regression model to predict the price a used car can fetch based on its attributes.
  - Evaluated the model by estimating the Mean Squared Error (MSE) and the percentage error in a sample of 20,000 entries from the dataset.

[Link to Dataset on Kaggle](https://www.kaggle.com/datasets/bartoszpieniak/poland-cars-for-sale-dataset)
