# Driver-Fatigue-Classification-with-EEG
 The project aimed at classifying driver fatigue during driving to prevent street accidents. Time series EEG data was utilized for the analysis, and the temporal features of the were extracted. Through feature engineering, the most effective features were chosen to train classifiers based on machine learning and deep learning.

This repository holds two folders: Data and Code

Data Folder: Data folder holds the features matrices extracted from all the subjects in both subject specific and subjects combined fashion. These matrices are direct input for training and testing the classifiers.

Code Folder: 4 Jupyter Notebook are inside this folder. The description are given below:
             i. Classification_DL.ipynb : This notebook demonstrates the classification of driver's fatigue with deep learning classifiers which are Long-Short Term Memory                                             (LSTM), 1 Dimennsional Convolutional Neural Network (1D-CNN) and Artificial Neural Network (ANN).
             
             ii. Value K for CV.ipynb: Finding the optimal value of K for cross validation has been demonstrated here. This value of K is used in the machine learning                                               classifiers.
             
             iii. Hyperparametric_Tuning_ML_Models.ipynb: After performing basic classification without any parameter tuning 4 ML classifiers are chosen for hyperparametric                                                    tuning based on their performance. This notebook includes sufficient codes for tuning.
             
             ii. Classification_ML.ipynb: This notebook demonstrates the classification of driver's fatigue with machine learning classifiers which are Logistic Regression,                                           K-Nearest Neighbor, Support Vector Machine, Rnadom Forest .
