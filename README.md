# Sparkify-ML_Pipeline
A feature engineering pipeline and ML model using PySpark, This Project is a part of Udacity Data Scientist Nanodegree.

Sparkify is an Music streaming platform just like Spotify. We have to create a ML model to predict customer churn based on the events data provided by Udacity.

I have also created a blog post on medium to give a step by step overview of this project:
https://gunanksood.medium.com/building-a-feature-engineering-pipeline-and-ml-model-using-pyspark-7036375cd081

## Project Instructions

## Libraries:

1. Python 3.6
2. PySpark ML
3. Jupyter
4. pandas

## Dataset: 
mini_sparkify_event_data.json this dataset is provided by udacity for this project.

## Files:
1. Sparkify.ipynb - This notebook contains the below mentioned steps which are required to complete this project.

## Steps in this project:

1. Data Cleaning
2. Feature Engineering 
3. Modeling
4. Results
 
Models used: Logistic Regression and Randomforest Classifier

Model Evaluation: Used F1 score and Accuracy to evaluate model performance.

In the blogpost, I have discussed on Important features for models and few ways to improve these results.

## Results

  F1 score:  0.826420504937
  Accuracy:  0.961674657232
  
It's important to choose the right set of metrics to evaluate a Machine learning Model, here I have chosen the f1 score and Accuracy of the model as an evaluation metric. F1 Score basically explains how robust and precise a machine learning model is, For these models, I did Hyper-parameter tuning on the basis of the F1 score only to improve the results of the model.

Initially, I started with the Logistic regression model I tried it with few parameters, Above screenshot shows the best I got from that, then I thought Random Forest can give better results here and after few hyper-parameter tweaks, it went ahead of the Logistic regression.

Random Forest Classifier gave better results here on the test dataset as compare to Logistic regression with an F1 score of 0.83 and Accuracy of 96%.

## acknowledgement
For issues related to PySpark syntax i refer to PySpark documentation and also i found solutions to most of the issues related to pySpark on stack Overflow.
https://spark.apache.org/docs/latest/api/python/index.html

To understand this project, this will be very helpful:
https://gunanksood.medium.com/building-a-feature-engineering-pipeline-and-ml-model-using-pyspark-7036375cd081

