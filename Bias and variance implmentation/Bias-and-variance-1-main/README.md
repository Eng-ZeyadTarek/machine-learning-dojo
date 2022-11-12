# CSAI 801 Lab 3: Bias and Variance 

1. Calculating Bias and Variance

In this question you are going to calculate the bias and variance of your
trained model.

- How to Re-sample data

You have been provided a dataset consisting of pairs (xi, yi). It can be loaded 
into your python program using pickle.load() function. Split the dataset into 
training and testing(90:10 split). Now divides the train set into 10 equal 
parts randomly, so that you will get 10 different dataset to train your model.


- Task

After re-sampling data, you have 11 different datasets ( 10 train sets and 1
test set). Train a linear classifier on each of the 10 train set separately, so 
that you have 10 different classifiers or models. You have 10 different models
or classifiers trained separately on 10 different training set, so now you can 
calculate the bias and variance of the model. You need to repeat the above 
process for the following class of functions.

          1.2.1 y = mx + c

          1.2.2 y = ax2 + bx + c
          
          1.2.3 y = ax4 + bx3 + cx2 + dx + e
          
And so on up till polynomial of degree 9. 

You are only supposed to use sklearn’s linear_model.LinearRegression().fit() for finding the appropriate coefficients with the default parameters. Tabulate the values of 
bias and variance and also write a detailed report explaining how bias and variance changes as you vary your function classes.

Note: Whenever we are talking about the bias and variance of model, it  refers to the average bias and variance of the model over all the test points.
