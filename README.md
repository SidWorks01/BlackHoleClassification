# BlackHoleClassification

## Introduction

The objective of this project is to identify the type of black hole using a dataset provided for the "BlackHole Classification" competition on Kaggle. The analysis involves data preprocessing, exploratory data analysis, feature engineering, and model building where I tried different models and approaches and recorded them to predict the target variable related to the conditions of the black hole.

## Data Description

The dataset contains various features, including luminosity and radio freq information. Key columns include:
- Multiple numerical and categorical features representing data.

## Methodology

### Data Preprocessing

1. **Loading Data**: The data is loaded from CSV files.
2. **Handling Missing Values**: Missing values are addressed by imputation or removal.In our case we used KNN Imputing
3. **Encoding Categorical Variables**: Categorical variables are encoded using techniques like one-hot encoding.

### Exploratory Data Analysis (EDA)

- **Visualization**: Histograms, scatter plots, and correlation matrices are used to understand data distribution and relationships.
- **Summary Statistics**: Descriptive statistics provide insights into the central tendency and variability of features.

### Checking Outliers

- **Outliers**- these were casted out using methods like DBSCAN And Kneepointing

### Model Building

1. **Model Selection**: Various models, including Logistic Regression, Decision Trees, and Random Forest, are evaluated.
2. **Hyperparameter Tuning**: Grid search and cross-validation are used to optimize model parameters.
3. **Evaluation Metrics**: Models are evaluated using metrics such as accuracy, precision, recall, and F1-score.
4. **Model Testing**: Models like XGBOOST , CARTBOOSTING and VOTING classifiers were introduced.

### Results

- **Model Performance**: The performance of different models is compared, and the best-performing model is selected.
- **Feature Importance**: Key features contributing to the model's predictions are identified.

## Conclusion

The project successfully identifies the most significant features and builds a predictive model for classifying black holes. 
