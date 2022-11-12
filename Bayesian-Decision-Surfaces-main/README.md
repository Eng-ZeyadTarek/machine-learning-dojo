# Bayesian Decision Surfaces

- Part 1: 

You are provided a dataset in the file binclass.txt. In this file, the first two numbers on each line
denote the two features of the input **x**<sub>n</sub>, and the third number is the binary label **y**<sub>n</sub>, € {—1, +1}.

  

Implement a generative classification model for this data assuming **Gaussian conditional distributions** of the positive and negative class examples to be N(**x**|**μ**<sub>+</sub>,σ<sup>2</sup><sub>+</sub>**I**<sub>2</sub>) and N(**x**|**μ**<sub>-</sub>,σ<sup>2</sup><sub>-</sub>**I**<sub>2</sub>), respectively. Note that
here **I**<sub>2</sub> denotes a 2 x 2 identity matrix. Assume the class-marginal to be **p(y<sub>n</sub> = 1) = 0.5**, and use **MLE**
estimates for the unknown parameters. Your implementation need not be specific to two-dimensional inputs and
it should be almost equally easy to implement it such that it works for any number of features (but it is okay if
your implementation is specific to two-dimensional inputs only).
 
On a two-dimensional plane, plot the examples from both the classes (use different colors for two classes) and the learned decision boundary for this model. Note that we are not providing any separate

test data. Your task is only to learn the decision boundary using the provided training data and visualize it.


Next, repeat the same exercise but assuming the Gaussian class-conditional distributions of the positive and
negative class examples to be  N(**x**|**μ**<sub>+</sub>,σ<sup>2</sup><sub>+</sub>**I**<sub>2</sub>) and N(**x**|**μ**<sub>-</sub>,σ<sup>2</sup><sub>-</sub>**I**<sub>2</sub>), respectively.
 
<hr>

- Part 2: 

Repeat the same experiments as you did for part | but now using a different dataset binclassv2.txt.

Looking at the results of both the parts, comments on the produced results with your own
findings. Include your plots (use a separate, appropriately labeled plot, for each case) and
experimental findings in the main writeup PDF. Please comment the code so that it is easy to
read and also provide a README that briefly explains how to run the code.
