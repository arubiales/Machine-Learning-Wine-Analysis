# Machine Learning Wine Analysis
This is a project where we realize different kind of analysis to predict wine color and quality. This project is divided in 4 files
1. Understand and preprocess the data: an EDA
2. Machine learning classification model to predict the wine color: if the wine is white or red
3. Machine learning regression model to predict the wine quality: to predict the quality of the model
4. Machine learning multi-classification model to predic the quality of the wine: quality goes from 0 to 10 but is not continual, it's categorical, so we can solve the problem predicting the different classes of quality

We are going to use diferent algorythms and his hyperparameters to fit and find the best model for our task, and make little explanations about them.  

The model that we are going to use are: SVM, Linear Regresion, Logistic Regresion, Decission Tree, Random Forest, Baggin with Logistic and Linear Regressions, KNeighbors and **XGBOOST** one of the most popular models in recent years who is obtaining the best results in the majority of the Machine Learning Kaggle competitions.

We are also going to see other functions to help cleaning and preprocessing techniques as Pandas Profiling or GridsearCV that helps us to select the best hyperparameters for the models (with expensive computer cost almost always).

The purpose of this project is to carry out in a practical and fast way how to receive some data, prepare them, train them and choose the best model to take it to production. So I will not expand on the explanation of the models themselves or in other terms.

This dataset has been download from the [University of California, Irvine](https://archive.ics.uci.edu/ml/datasets/wine) but i have modify a little bit so if you want to get the same results as me, you have to use the dataset from this repository.

This repository have:
* Data directory: where is the original dataset and the transformations to the models
* Model_saved directory: where is the diferent models that we have trained
* The notebooks where we implement the differents Machine Learning methods
