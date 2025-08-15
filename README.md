# Nutriclass_Food-Classification

This project involves developing a Machine Learning model that classifies food into multiple categories. It compares traditional Machine Learning models on food classification
and gives an insight into which feature extraction and model combination performs best by visually representing the comparison of different Classification models and their respective evaluation metrics.

## Installation

To install the project the following packages are needed to be imported(if not already present):

- pandas
- sklearn.preprocessing - StandardScaler, LabelEncoder
- sklearn.model_selection - train_test_split
- sklearn - metrics
- sklearn.linear_model - LogisticRegression
- sklearn - tree
- sklearn.neighbors - KNeighborsClassifier
- sklearn.ensemble - GradientBoostingClassifier, RandomForestClassifier
- sklearn.svm - SVC
- matplotlib.pyplot

To install packages run command on Windows: 
python -m pip install <Package Name>

# Execution / Usage

### 1. Clean the given data in 'synthetic_food_dataset_imbalanced.csv' file by:

    Removing duplicate values
    Handling missing/null values
    Removing irrelevant columns

### 2. Process the cleaned data by:

    Convert the non-numeric columns to numeric
    Apply standard scalar to all the columns except target 'Food_Name' column
    Split and set the Training and Testing Data for the models 
    Evaluate the input model based on input test data and display the evaluation metrics;
    (accuracy, precision, recall, f1-score and confussion matrix)
    Create a Bar plot to display comparison of Classification models vs their Accuracy scores
    
These steps are done in NutriClassification.ipynb file

#### To run the file:
Run the cells one by one in NutriClassification.ipynb
