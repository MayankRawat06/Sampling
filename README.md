# ML Sampling Techniques Comparison

This project compares the performance of 5 different machine learning models on 5 different sampling techniques for imbalanced datasets. 

### The sampling techniques used in this project are:

- Random Over-Sampling
- Random Under-Sampling
- SMOTE
- ADASYN
- Tomek Links
- Stratified Sampling
- Systematic Sampling

### The machine learning models used in this project are:

- Logistic Regression
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors
- XGBoost

### The project is implemented in Python using the following libraries:
- numpy
- pandas
- scikit-learn
- imbalanced-learn
- xgboost


### Comparision Table

| Model                  |   ADASYN |   Random Over-Sampling |   Random Under-Sampling |    SMOTE |   Stratified Sampling |   Systematic Sampling |   Tomek Links |
|:-----------------------|---------:|-----------------------:|------------------------:|---------:|----------------------:|----------------------:|--------------:|
| K-Nearest Neighbors    | 0.922414 |               0.943966 |                0.655172 | 0.918103 |              0.987069 |              0.987069 |      0.918103 |
| Logistic Regression    | 0.931034 |               0.935345 |                0.836207 | 0.926724 |              0.982759 |              0.982759 |      0.926724 |
| Random Forest          | 0.987069 |               0.987069 |                0.577586 | 0.987069 |              0.987069 |              0.987069 |      0.987069 |
| Support Vector Machine | 0.672414 |               0.676724 |                0.469828 | 0.672414 |              0.987069 |              0.987069 |      0.676724 |
| XGBoost                | 0.948276 |               0.969828 |                0.642241 | 0.948276 |              0.987069 |              0.982759 |      0.952586 |
