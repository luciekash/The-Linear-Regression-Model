# The-Linear-Regression-Model
Introduction

We started by building intuition for model based learning, explored how the linear regression model worked, understood how the two different approaches to model fitting worked, and some techniques for cleaning, transforming, and selecting features. In this project, you can practice what you learned by exploring ways to improve the models we built.

You'll work with housing data for the city of Ames, Iowa, United States from 2006 to 2010. You can also read about the different columns in the data here.

Let's start by setting up a pipeline of functions that will let us quickly iterate on different models.

Tasks

Import pandas, matplotlib, and numpy into the environment. Import the classes you need from scikit-learn as well.
Read AmesHousing.tsv () into a pandas data frame.
For the following functions, we recommend creating them in the first few cells in the notebook. This way, you can add cells to the end of the notebook to do experiments and update the functions in these cells.
Create a function named transform_features() that, for now, just returns the train data frame.
Create a function named select_features() that, for now, just returns the Gr Liv Area and SalePrice columns from the train data frame.
Create a function named train_and_test() that, for now:
Selects the first 1460 rows from from data and assign to train.
Selects the remaining rows from data and assign to test.
Trains a model using all numerical columns except the SalePrice column (the target column) from the data frame returned from select_features()
Tests the model on the test set and returns the RMSE value.
