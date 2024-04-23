# Credit Score Prediction: Identifying Potential Defaulters

## Overview
The objective of this case study is to identify borrowers likely to fall into serious delinquency, specifically more than 3 months overdue, in the next 2 years. By accurately predicting potential defaulters, banks can take necessary actions to mitigate risks and save money.

### Data Overview
The dataset contains records of 150,000 borrowers, split into 80% training and 20% test data. The target variable is binary, indicating serious delinquency (1) or not (0). The dataset includes mixed continuous and categorical features, with missing values in two columns. Class imbalance is observed, with 6.7% of customers experiencing serious delinquency.

## Libraries Used
- Pandas
- Matplotlib
- Seaborn
- NumPy
- Scikit Learn
- Imblearn
- Shap
- LIME
- Keras

## Code Overview

1. **Modeling Setup**: Split data into training and test sets.
2. **Data Preprocessing**: Handle missing values, remove outliers, and clean data.
3. **Feature Engineering**: Create new features to enhance model performance.
4. **Class Imbalance Handling**: Employ upsampling, downsampling, and synthetic sampling techniques.
5. **Feature Scaling**: Scale features for certain models.
6. **Model Building**: Train various models including Neural Networks, Logistic Regression, and Tree-based models.
7. **Hyperparameter Tuning**: Optimize model performance using GridSearchCV.
8. **Model Evaluation**: Assess models using metrics beyond accuracy.
9. **Model Interpretability**: Utilize SHAP and LIME for global and local model interpretability.

## Project Structure
```
|-- InputFiles
    -- cs_data.csv
|-- SourceFolder
    |-- ML_Pipeline
        -- data_preprocessing.py
        -- data_splitting.py
        -- data_transformation.py
        -- dataset.py
        -- feature_engineering.py
        -- model_params.py
        -- predict_model.py
        -- scaling_features.py
        -- train_model.py
        -- upsampling_minorityClass.py
    |-- Engine.py

