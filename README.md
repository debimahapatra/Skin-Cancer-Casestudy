# Project Name
> Skin cancer ISIC The International Skin Imaging Collaboration Case Study


## Table of Contents
* [Problem Statement](#problem-statement)
* [Assumptions](#assumptions)
* [Technologies Used](#technologies-used)
* [Final Model](#final-model)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contacts](#contacts)


## Problem Statement
- In this assignment, you will build a multiclass classification model using a custom convolutional neural network in TensorFlow. 

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Assumptions
- NA


## Technologies Used
- Language - Python
- library - Numpy
- library - Pandas
- library - matplotlib
- library - seaborn
- library - math
- Library - statsmodel
- Library - sklearn

## Final Model
- Model Type: CNN
- Optimizer: Adam
- Loss Function: Cross Entropy

## Conclusions
-We can see some improvement in overfitting in comparison to the earlier executed models.
With Epoch 30:
Accuracy: 88%
Val_Accuracy: 65%

With increase in Epoch to 50 the accuracy went above 90% and val_accuracy was aroudn 80%.(as per the upgrad casestudy I am just keeping it as 30 for the epoch)

## Acknowledgements
- This project is part of a case study from Upgrad for skin cancer image detection


## Contacts
- Created by [@debimahapatra]
