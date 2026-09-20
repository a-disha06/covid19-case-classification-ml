# COVID-19 Case Classification Using Machine Learning

## Project Overview
This project analyzes a global COVID-19 country-level dataset and applies machine-learning classification techniques to identify countries with high total COVID-19 cases.

## Objectives
- Clean and preprocess COVID-19 data
- Handle missing values
- Perform exploratory data analysis (EDA)
- Create a binary classification target
- Train machine-learning classification models
- Compare model performance
- Visualize feature importance and PCA

## Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Load the dataset
2. Inspect the data
3. Clean numeric columns
4. Remove summary rows
5. Analyze missing values
6. Perform exploratory data analysis
7. Create the target variable
8. Split the data into training and testing sets
9. Preprocess the features
10. Train classification models
11. Evaluate the models
12. Analyze feature importance
13. Apply PCA visualization

## Dataset
The notebook expects the dataset file:

`COVID-19 Global - Dataset.csv`

Keep the CSV file in the same folder as the notebook before running it.

## Important Note
The target is created from `Total Cases` using the dataset median as a threshold. `Total Cases` is therefore excluded from the model input features to avoid direct target leakage.

## Future Improvements
- Use a larger and more recent time-series dataset
- Add cross-validation
- Perform hyperparameter tuning
- Explore more meaningful prediction targets
- Add additional visualizations and statistical analysis
