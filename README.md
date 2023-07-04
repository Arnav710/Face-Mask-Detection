## Overview

Built an image classifier for detecting whether a person is wearing a mask or not in Python. The model for the same was trained
on a dataset of 12,000 images and the model was able to achieve an accuracy greater than 98% on thetesting dataset which
contained 1,000 images.

## Summary
This program is created to look at images and tell whether the person in the image is wearing a mask or not. The model was able to detect whether a person is wearing a mask with an accuracy of 98% on the testing dataset. The dataset for this binary classification problem was taken from kaggle. This is the link for the dataset: Face Mask ~ 12k Images Dataset. This model can be used in workplaces to check whether a person is wearing a mask, thus allowing a person to enter a building only if he/she is wearing a mask. The following are the components of this program:

- Importing libraries
- Loading the dataset from the kaggle directory
- Splitting the training data into separate numpy arrays of images and their labels
- Splitting the testing data into separate numpy arrays of images and their labels
- Defining the model
- Compiling the model
- Fitting the model
- Visualising the accuracy and loss during the training
- Evaluating the model on the testing dataset
- Visualising predictions made on some images from the validation dataset
