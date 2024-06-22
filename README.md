# X-Analysis

This repository contains the analysis and implementation of various machine learning models for X(formerly known as Twitter). The models included in this analysis are:

- Logistic Regression with "Count Vectors" method
- Logistic Regression with "TF-IDF" method
- XGBoost with "Count Vectors" method
- XGBoost with "TF-IDF" method
- LightGBM with "Count Vectors" method
- LightGBM with "TF-IDF" method

Additionally, we have evaluated the performance of these models using the ROC AUC (Receiver Operating Characteristic - Area Under Curve) metric.

## Data

The data used in this analysis is a collection of tweets. The preprocessing steps include cleaning the text, tokenization, lemmatization and converting the text into numerical representations using "Count Vectors" and "TF-IDF" methods.

## Models

### Logistic Regression

Logistic Regression is a simple yet effective classification algorithm. We have trained Logistic Regression models using both "Count Vectors" and "TF-IDF" methods to convert text data into numerical form.

### XGBoost

XGBoost is a powerful gradient boosting algorithm. It is known for its performance and speed. We have trained XGBoost models using both "Count Vectors" and "TF-IDF" methods.

### LightGBM

LightGBM is another gradient boosting framework that is known for its efficiency and high performance. We have trained LightGBM models using both "Count Vectors" and "TF-IDF" methods.

## Evaluation

The performance of the models is evaluated using the ROC AUC metric. The ROC AUC curve provides an aggregate measure of performance across all possible classification thresholds. 

## Results

The following are the results of our analysis, comparing the performance of each model:

| Model                           | Count Vectors AUC | TF-IDF AUC |
|---------------------------------|-------------------|------------|
| Logistic Regression             | 0.950             | 0.938      |
| XGBoost                         | 0.945             | 0.943      |
| LightGBM                        | 0.934             | 0.937      |

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any features, bug fixes, or enhancements.
