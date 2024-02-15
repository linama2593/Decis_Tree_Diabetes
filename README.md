# Diabetes Decision Tree & Random Forest Classifier 🩺🌳

This repository focuses on predicting whether a patient has diabetes using data from the National Institute of Diabetes and Digestive and Kidney Diseases. The prediction is performed using a decision tree classifier and a random forest classifier.

## Notebooks 📓

All the main code and analysis can be found in the `src` folder. Here's a breakdown of the notebooks:

- [`Diabetes_Data-EDA.ipynb`](src/Diabetes_Data-EDA.ipynb): This notebook contains the exploratory data analysis.

- [`Diabetes_DecisTree.ipynb`](src/Diabetes_DecisTree.ipynb): Here, you can find all the estimations and performance evaluations for the decision tree classifier.

- [`Diabetes_RandomForest.ipynb`](src/Diabetes_RandomForest.ipynb): This notebook compares the performance, measured by accuracy, of the optimized decision tree classifier with that of a random forest classifier.

## Folders 📁

### `data/interim/`

This folder contains the training and testing covariate (X) data without handling missing values.

### `data/processed/`

Here, you'll find the processed data:

- `X_train` and `X_test`: Covariate (X) train and test data after replacing missing values.
- `y_train` and `y_test`: Train and test data for the dependent variable (y).

### `models/`

The `models` folder stores the models resulting from the analysis and estimations.

Feel free to explore the notebooks and folders to understand the process and results of predicting diabetes using decision trees and random forests. If you have any questions or suggestions, please don't hesitate to open an issue or contribute to the project. Happy coding! 🚀
