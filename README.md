![](https://github.com/PrachiPatel15/Detecting-Parkinson-s-Disease/blob/main/disease.png)

Parkinson’s disease is a progressive disorder of the central nervous system affecting movement and inducing tremors and stiffness.
This is chronic and has no cure yet. It is a neurodegenerative disorder affecting dopamine-producing neurons in the brain.

# Detecting Parkinson's Disease: Project Overview
- Created a project in which we can accurately detect the presence of Parkinson’s disease in one’s body.
- Did feature scalling on the attributes.
- Build a model using XGBoost to predict the accurate result.

# Code and Resources Used
- ***Python Version:*** 3.7
- ***Packages:*** pandas,XGBoost
- ***Dataset:*** https://archive.ics.uci.edu/ml/machine-learning-databases/parkinsons/

# EDA
- In the data analysis part, we first initialize a MinMaxScaler and scale the features to between -1 and 1 to normalize them. The MinMaxScaler transforms features by scaling them to a given range. The fit_transform() method fits to the data and then transforms it.  

# Model Building
-  In the model building part, we initialize an XGBClassifier and train the model. It falls under the category of Ensemble Learning in ML, where we train and predict using many models to produce one superior output.

# Summary
- In this Python machine learning project, we learned to detect the presence of Parkinson’s Disease in individuals using various factors. We used an XGBClassifier for this and made use of the sklearn library to prepare the dataset. This gives us an accuracy of 94.87%, which is great considering the number of lines of code in this python project.
