![alt text](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/01/python-machine-learning-project-handwritten-digit-recognition-1-640x480.jpg)

# Handwritten-Digit-Recognizer
  
## Table of content
  * [Overview]
  * [Installation]
  * [Project Details]
  * [Technologies used]
  
## Overview
Credit is part of your financial power. It helps you to get the things you need now, like a loan for a car or a credit card, based on your promise to pay later. Working to improve your credit helps ensure you'll qualify for loans when you need them.

![alt text](https://mygreatlakes.org/mglstatic/educate/images/knowledge-center/interactive-assets/credit/good-credit-man.png)

In this project, i have built a model based on credential data of some customers declaring whether they are eligible for credit or not. This model will predict whether a customer is having a "Good" or "Bad" credit status.

## Installation
The code is written in Python 3.7 in Jupyter Notebook. If you dont have it you can first download Anaconda platform [here](https://docs.anaconda.com/anaconda/install/), where You will find the Jupyter Notebook within it. Jupyter Notebooks are powerful, versatile, shareable and provide the ability to perform data visualization in the same environment.It also allows data scientists to create and share their documents, from codes to full blown reports. They help data scientists streamline their work and enable more productivity and easy collaboration. Due to these and several other reasons you will see below, Jupyter Notebooks are one of the most popular tools among data scientists.

After installing Anaconda, you have to install two packages-
1. "Scikit Learn" library for preprocessing the data. You can install Scikit Learn [here.](https://scikit-learn.org/stable/install.html)
2. "keras" library to build the model. For that you have to run the following code in anaconda prompt.
`pip install keras`

After completing the installation process, run the Jupyter Notebook where you can use the code (`CNN Handwritten.ipynb`).

## Project Detail
Here, in this project, the data i have used is in the format of csv file i.e `creditcard.csv` which is located in my 'D:' drive. You can change the path of the loaction of the file as you want. The data consist of personal details of a customer like "NPA Status",	"Age",	"Gender",	"Region",	"MonthlyIncome",	"Rented_OwnHouse",	"Occupation",	"Education", "DebtRatio", "NumberOfDependents", etc. After analysing the data(i.e removing null values, modifying some unrelated variables based on some criteria, etc) i have finally built the model using simple Logistic Regression to predict credit status of any given data of a customer.

## Technologies Used
![](https://forthebadge.com/images/badges/made-with-python.svg)
![](https://i.redd.it/c6h7rok9c2v31.jpg)
![](https://twilio-cms-prod.s3.amazonaws.com/original_images/jupyter_python_numpy.png)
![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/scikit-learn-logo.png)


