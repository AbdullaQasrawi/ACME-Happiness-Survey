ACME Happiness Survey Model
This repository contains the code for a machine learning model that is trained on the ACME Happiness Survey dataset provided by Apziva. The goal of the model is to predict customer satisfaction based on survey responses.

Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
The following packages are required to run the code:

pandas
scikit-learn
pickle
You can install these packages by running the following command:
pip install -r requirements.txt

Running the Model
The code for the model can be found in the train.py file. To train the model, run the following command:
python train.py

The model will be trained on the ACME-HappinessSurvey2020.csv dataset and the accuracy will be printed.

The inference.py file contains the code for using the trained model to make predictions on new data.

Model Evaluation
The model uses Decision Tree Classifier algorithm with accuracy_score as evaluation metric.

Built With
Scikit-learn - Machine Learning Library
Pandas - Data Manipulation Library
Pickle - Python object serialization library

Authors
Abdallah Kasrawi 
