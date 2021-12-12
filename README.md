# Credit_Risk_Analysis

# Overview
In this assignment we are using different methoods to predict credit risk using a dataset of of customer
loans. Using 2 methods (Oversampling and Ensemble Classifiers) to complete this task.
The means to conduct this evaluation were done with the following
Naive Random Oversampler
SMOTE,
Cluster Centroids,
SMOTEENN,
Balanced Random Forest Classifier,
Easy Ensemble AdaBoost Classifier

# Results

# Ensemble
Easy Ensemble

![Screenshot 2021-12-12 174817](https://user-images.githubusercontent.com/25463509/145732858-6f7d6605-b211-4d57-9b9d-6744f0c77c81.png)



Random Forest

![Screenshot 2021-12-12 175332](https://user-images.githubusercontent.com/25463509/145732866-838563e5-189f-4846-8dc6-d0094a038329.png)

# Resampling

Random Resampling
![Screenshot 2021-12-12 180033](https://user-images.githubusercontent.com/25463509/145733082-19d02eaf-975d-470a-a438-c604979e4d59.png)


SMOTEEN

![Screenshot 2021-12-12 181841](https://user-images.githubusercontent.com/25463509/145733650-b48b4204-7207-40a9-ac86-9ffd7f0059a6.png)

Undersampling

![Screenshot 2021-12-12 182851](https://user-images.githubusercontent.com/25463509/145733998-b5a5d08c-a7b3-4ee8-8ff8-698484d077de.png)



Random Forest: 78% accurate

Easy Ensemble : 92% accurate

Random Resampling: 64% accurate

SMOTE Oversampling: 62% accurate

Undersampling : 54% accurate

SMOTEEN Over/under :62%

# Summary
After all the models were ran the most accurate that i would reccomend is the Easy Ensemble because of its high accuracy (92%) and its
high precision and recall. Other models had decenct accuracy but lacked in other fields such as recall and precision.
