# house-prices-advanced-regression-techniques
This dataset from kaggle can be found at : https://www.kaggle.com/c/house-prices-advanced-regression-techniques

This is an interview question for me which is as follows :

## Task Description
 
Your task is to rapidly load, understand, and build a machine learning model for house price data. 
 
Your deliverable should include:
* A machine learning model trained on the SalePrice (hint: train the model on log(SalePrice))
* An evaluation of the predictions, score them using RMSE of the log(prediction) vs. the log(SalePrice)
* Evidence that your model is capable of generalizing (e.g. cross-validation)
* Evidence that your model score or predictions are reasonable (e.g. benchmarking)
 
You are allowed:
* 30 minutes to complete the exercise
* Any language and IDE of your choosing
* Internet
 
You are not allowed:
* To search www.kaggle.com for solutions
 
The following is not required but considered a plus:
* Data visualization
* Multiple models
* Feature engineering
* Feature importance
 
 
Task Milestones
These are the major milestones to be completed by a successful candidate.
Load the data
Gain some understanding of the data
Feature selection/building
Train a model and make predictions
Score the predictions (should be out-of-sample)
Provide generalization evidence (e.g. cross-validation)
Provide evidence that predictions are reasonable (e.g. benchmarking)

My solution 
====================================================================================================================================
1)Rapid ETL is conducted via softwares Trifacta and Python Orange Package can also be used.

2)Assesment of missing values, outliers and transforming via Trifacta or Orange

3)Feature Engineering and Feature importance assessment report using Orange 

4)Data preparation for Neural Network 

5)Selection of appropriate Non-Temporal Neural Network for the data 

•GFF = Generalized Feedforward

•LReg = Linear/Logistic Regression

•MLP = Multi-layer Perceptron

•MOD = Modular Network

•PNN = Probabilistic Network

•SVM = Support Vector Machine

Number of Hidden Layers:Tried with 1, 2 

Learning Algorithm

This acronym represents the learning algorithm used on the backpropagation plane.The following methods were tried  :

•CG = Conjugant Gradient

•LM = Levenberg-Marquardt

•MOM_B = Momentum (Batch Learning)

•MOM_O = Momentum (Online Learning)

•RProp = Resilient Backpropagation

The neural network parameter optimization used is PNN Smoothing (Beta).
