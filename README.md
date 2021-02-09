# Sentiment Analysis with SageMaker - Deployment Project

The notebook and Python files provided here, result in a simple web app which interacts with a deployed recurrent neural network (RNN/LSTM) performing sentiment analysis on movie reviews. This project required some familiarity with SageMaker, because of that we needed to complete and undestand the mini-project, Sentiment Analysis using XGBoost, provided enough background to understand the main SageMaker resources to complete this project.

This project is the first one of the Machine Learning Engineer Nanodegree program from Udacity and was approved to a specialist from Udacity after first commit.

## Results

![Deployed model using a local web app - Positive Review](https://github.com/rodolfojt/Sentiment-Analysis-SageMaker/blob/master/assets/Results%20-%20Positive%20Review.PNG)

![Deployed model using a local web app - Negative Review](https://github.com/rodolfojt/Sentiment-Analysis-SageMaker/blob/master/assets/Results%20-%20Negative%20Review.PNG)

## Services Flow

![Services Flow](https://github.com/rodolfojt/Sentiment-Analysis-SageMaker/blob/master/Web%20App%20Diagram.svg)

## AWS Resources used to Deployment

- AWS SageMaker
- AWS API Gateway
- AWS Lambda

## Dependencies

- sagemaker
- pytorch
- scikit-learn
- numpy
- pickle
- pandas
- boto3

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory of the Udacity GitHub Page for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).
