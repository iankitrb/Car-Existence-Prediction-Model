Car Existence Prediction Model


This project is focused on building a machine learning model to predict whether a specific car exists in a dataset. The dataset contains information about cars, including their unique ID, a binary indicator of existence, and a comment column describing the closest matching model. The goal is to train a machine learning model (Random Forest Classifier) using the exists column as the target variable for classification based on the given features.

Dataset
The dataset consists of the following columns:
id, exists, comment

Project Steps

Data Loading & Preprocessing:
The dataset is loaded, and missing values in the exists column are handled.
The exists column is transformed from categorical (yes/no) to numerical (1/0).
Textual data from the comment column is processed to extract meaningful features for use in model training.

Feature Engineering:
The comment column is transformed into numerical data that can be used for training the model.
A Random Forest Classifier is trained using the extracted features from the comment column and the transformed exists target variable.

Model Evaluation:
The model is evaluated using accuracy, precision, recall, and a confusion matrix to assess its performance.
