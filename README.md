# explainableAI_tutorial

## Preproccessing file: ESIP_preprocessing.ipynb

This file describes some of the basic steps in preproccessing data. The file called minimal_preprocessing.csv contains data that was already compiled by me from the CRMS stations. However, the only preprocessing done before what is shown in the ESIP_preprocessing.ipynb file is concatenation of dataframes and averaging using the .groupby method of pandas. 

## Machine Learning Tutorial: ESIP_tut_1_23_draft5.ipynb

Here is the whole tutorial on expainable AI. A summary is provided above for those interested in skipping to specific section of the tutorial. The structure of our tutorial follows below.

### Motivation
Here we outline machine learning in the earth sciences and our specific use case. Advantages and disadvantages of machine learning are highlighted as well as the definition of explainable AI. 

### Machine Learning Tools
This is an expansive section in our tutorial. We begin by explaining linear regression, then explaining Bayesian Linear Regression (BLR) since this is a model we will implement in the tutorial. We then introduce the machine learning explainability python package called SHAP on the BLR. 

Next, we introduce the Gaussian Process Regression Model. We implement this model using the scikit learn python library and conduct the same SHAP analysis on the GPR model to compare against the BLR SHAP analysis.

### Data Preparation

Data Preparation is conducted primarily in the ESIP_preprocessing.ipynb file. Other preparations are done in the "Data Descriptions" portion of the tutorial and in scaling the the features. 

### Hyperparameter Tuning

The only example of hyperparameter tuning comes in the 
