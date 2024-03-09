# Iris Flower Classification

## Overview

The Iris Flower Classification project aims to develop a machine learning model that can accurately classify Iris flowers into different species based on their sepal and petal measurements. The dataset used in this project is the well-known Iris dataset, consisting of three species: setosa, versicolor, and virginica.

## Dataset

The dataset used in this project is loaded from the "IRIS.csv" file. It includes measurements of sepal length, sepal width, petal length, petal width, and the corresponding species label.

## Exploratory Data Analysis (EDA)

- **Basic Information**: The dataset is explored to understand its structure and features.
- **Data Visualization**: Various plots and visualizations are created to understand the relationships between different features and the distribution of the target variable.

## Data Preprocessing

- **Label Encoding**: The target variable 'species' is label-encoded for model training.
- **Feature Scaling**: Min-Max scaling is applied to normalize the feature values.

## Model Building

- **K-Nearest Neighbors (KNN) Classifier**: The KNN algorithm is employed for classification. The model is trained on both the original and PCA-transformed datasets.

## Evaluation

- **Accuracy Scores**: The accuracy of the KNN classifier is evaluated on both the original and PCA-transformed datasets.
- **Elbow Method**: The Elbow Method is employed to determine the optimal number of neighbors (k) for the KNN classifier.

## Custom KNN Implementation

- A custom implementation of the KNN algorithm is provided for better understanding.
- The accuracy and error are visualized for different values of k.

## Files Included

- `IRIS.csv`: The dataset file.
- `iris_classification.ipynb`: Jupyter Notebook containing the code for data exploration, preprocessing, model building, and evaluation.
- `readme.md`: Documentation file.

## How to Run

1. Ensure you have the necessary libraries installed. You can install them using:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn


## Acknowledgments
This project was created as part of a data science initiative and is meant for educational purposes.

## License
This project is licensed under the [MIT License](LICENSE).

