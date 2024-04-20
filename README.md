# Decision_Tree_Classifier_-_Random_Forest_Classifier_-Credit_Card_Fraud_Detection

## Overview
This project aims to detect credit card fraud using machine learning models, specifically Decision Tree Classifier and Random Forest Classifier. The dataset used for this project contains information about credit card transactions, including various features and a binary target variable indicating whether a transaction is fraudulent or not.

## Steps

### 1. Importing Libraries
   - Necessary libraries such as numpy, pandas, matplotlib, seaborn, and scikit-learn are imported.
   - `pandas-profiling` is mentioned for generating reports and graphical analysis.

### 2. Importing the Dataset
   - The dataset (`creditcard.csv`) containing credit card transaction information is imported using pandas.

### 3. Data Analysis
   - Basic exploratory data analysis (EDA) is performed, including checking the shape, info, description, and target variable distribution of the dataset.
   - Correlation analysis is visualized using a heatmap.

### 4. Handling Imbalanced Data
   - Techniques to handle imbalanced datasets are discussed, including random under-sampling, random over-sampling, and the use of `imblearn` library.
   - Feature importance analysis using `ExtraTreesClassifier` is performed to identify significant features.

### 5. Feature Selection
   - Two scenarios for feature selection are discussed: one with all 28 features and the other with only the top 18 important features.

### 6. Splitting Data into Sets
   - Data splitting is performed using `StratifiedKFold` to ensure class balance in training and testing sets.

### 7. Model Selection
   - Decision Tree Classifier and Random Forest Classifier are chosen as the models for credit card fraud detection.

### 8. Hyperparameter Tuning (Random Forest Classifier)
   - Randomized hyperparameter tuning is applied to the Random Forest Classifier using `RandomizedSearchCV`.

### 9. Train the Model
   - The Random Forest Classifier model is trained on the training data.

### 10. Test the Model
   - The trained model is used to make predictions on the test data.

### 11. Performance Metrics
   - Performance metrics such as confusion matrix and accuracy score are calculated to evaluate the model's performance.

## Additional Resources
- Techniques for dealing with imbalanced datasets are provided with relevant links for further reading.
- Suggestions for further exploration include using `imbalanced-learn`, `lazypredict`, and `auto-sklearn` for automating machine learning tasks.

## Dependencies
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `imbalanced-learn`
- `lazypredict`
- `auto-sklearn`
