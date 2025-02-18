# Cardiovascular Disease Classification

The objective of this classification analysis is to develop a machine learning model to predict the likelihood of cardiovascular disease (CVD) or heart disease in individuals based on the provided 11 attributes. We also analyze the relationships between risk factors (e.g., hypertension, diabetes, hyperlipidemia) and cardiovascular outcomes, and identify the most influential features contributing to heart disease, guiding public health initiatives.

## Models 
We employed three different machine learning algorithms to predict the likelihood of heart disease:

- K-Nearest Neighbors (KNN): A non-parametric method used for classification, where the class of a sample is determined by the majority class among its nearest neighbors.

- Decision Tree: A tree-like model used for classification, which splits the data based on feature values to make predictions. We use Grid Search CV to fine-tune hyperparameters for better performance. We utilized Grid Search CV to tune the hyperparameters of the Decision Tree model to find the optimal configuration and improve model performance.

- Gradient Boosting: An ensemble method that builds models sequentially, with each model correcting the errors of the previous one. It is effective in improving accuracy by combining weak learners

## Model Evaluation 
 - The accuracy of the three models were calculated and compared.
   
