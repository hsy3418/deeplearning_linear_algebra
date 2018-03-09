


# deeplearning_linear_algebra

This project has solved a linear regression problem using the basic of machine learning algorithm, the implementation is not using any external libraries.

## Prerequisites

The jupyter notebook has been installed

## Get Started

Download the whole project, and run the linear_regression_project(1).ipynb


## Unit test
You can use unit tests to ensure all your implementations meet requirements, but make sure you include the test.py file in the folder.

The following are some examples of the assersion error. 

- AssertionError: Matrix A shouldn't be modified
  + Your augmentMatrix modifies matrix A. 
  
- AssertionError: Matrix A is singular
  + Your gj_Solve doesn't return None when A is singular. 
- AssertionError: Matrix A is not singular
  + Your gj_Solve returns None when A is not singular.
- AssertionError: x have to be a two-dimensional Python list
  + Your gj_Solve returns with incorrect data structure. X should be a two a list of lists. 

- AssertionError: Regression result isn't good enough
  + Your gj_Solve has too much error. 
