# Wine Wizardry: Unraveling the Secrets of Fine Wine
_By Donal Moloney_

Welcome to "Wine Wizardry", a project that merges the world of viticulture with the realm of data science. Journey with us as we unlock the secrets behind fine wines using machine learning and data analysis techniques.

## Project Overview

This project delves into the Wine dataset, exploring its intricacies using visualizations, data cleaning, and feature engineering. We then apply machine learning models, specifically Random Forests, to classify wines based on their attributes. Further, we interpret these models using SHAP values and visualize our results.

## Installation

To set up and run the project, you'll need to install the following packages:

```bash
pip install numpy pandas scikit-learn seaborn matplotlib shap
```
## Data Exploration

We convert the Wine dataset into a Pandas DataFrame and explore its basic statistics, visualize class distribution, and more. The data comprises 178 samples, each with 14 numerical attributes, ideal for data analysis and machine learning.


## Model Training and Evaluation

In this segment, we split our data, train a Random Forest Classifier, and evaluate its performance using cross-validation. Techniques such as GridSearchCV and RandomizedSearchCV help us optimize hyperparameters for our model.

## Interpretability with SHAP

After building the model, it's crucial to understand the reasons behind its predictions. SHAP (SHapley Additive exPlanations) values give us insight into how each feature contributes to individual predictions.

## Feature Engineering and Selection

Exploiting the power of domain knowledge, we derive new features that provide additional insights and improve the model's performance. Also, we analyze the importance of each feature and make data-driven decisions to select the most significant attributes.

## Conclusion

The journey of wine wizardry offers a perfect blend of viticulture and data science. This project showcases the potential of modern machine learning and analysis techniques in deriving meaningful insights from intricate datasets. Cheers to the fusion of wine and wizardry!


