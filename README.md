
# Phishing Domain Detection by machine learning techniques iNeuron Internship



## Objective 
To predict whether the domain is real or malicious.

## Dataset
Phishing Websites Dataset

https://data.mendeley.com/datasets/72ptz43s9v/1

These data consist of a collection of legitimate as well as phishing website instances. Each website is represented by the set of features which denote, whether website is legitimate or not. Data can serve as an input for machine learning process.

In this repository the two variants of the Phishing Dataset are presented.

Full variant - dataset_full.csv
Short description of the full variant dataset:
Total number of instances: 88,647
Number of legitimate website instances (labeled as 0): 58,000
Number of phishing website instances (labeled as 1): 30,647
Total number of features: 111

Small variant - dataset_small.csv
Short description of the small variant dataset:
Total number of instances: 58,645
Number of legitimate website instances (labeled as 0): 27,998
Number of phishing website instances (labeled as 1): 30,647
Total number of features: 111
## Demo
here is the demo of my project 



https://youtu.be/qpgXtscmWIg
## Model Training 
Before stating the ML model training, the data is split into 80-20. From the dataset, it is clear that this is a supervised machine learning task. There are two major types of supervised machine learning problems, called classification and regression.

This data set comes under classification problem, as the input URL is classified as phishing (1) or legitimate (0). The supervised machine learning models (classification) considered to train the dataset in this project are:

Decision Tree
Random Forest
Multilayer Perceptrons
XGBoost
Autoencoder Neural Network

All these models are trained on the dataset and evaluation of the model is done with the test dataset.
## End Result
From the obtained results of the above models, XGBoost Classifier has highest model performance of 96.5%. So the model is saved to the file