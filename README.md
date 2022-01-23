# Starbucks Capstone Project using AWS SageMaker

This project implements Autogluon Tabular models on AWS Sagemaker.

- From three json files, I transform into related data on csv files.

- From this data, I analyze to have some logical conclusions and create train and test data for autogluon tabular model.

- I test on local machine with sklearn logistic regression model to have a quick review, and after that test it with autogluon tabular model.

- From the good results on local machine, I perform this autogluon tabular model on AWS from training, testing until deploying the endpoint on Aws.

- All the main ideas are witten in file ***proposal.pdf*** and ***report.pdf***.

## All in this repo

### 1. Folder code

- Aws Starbucks Capstone.ipynb
- ag_model.py
- config.yaml
- tabular_train.py
- tabular_serve.py

### 2. Folder data - data.zip - a small storage

- All the json files and csv files contain related data are used for this project

### 3. Folder images

- All the images are saved when my notebook executed on Aws Sagemaker Studio, training jobs, and endpoints.

### 4. File ***proposal.pdf***

### 5. File ***report.pdf***

### 6. File ***Aws Starbucks Capstone.html*** for easy review

### [Here is my blog post](https://ngandn18.github.io/project/proj_5.html)
