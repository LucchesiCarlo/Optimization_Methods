# Optimization Methods Project Work: SMO and DCD-Linear for SVMs

The objective of this Laboratory is to implement and confront two algorithms for training linear SVM: SMO and DCD.

## What to achieve

To confront the two algorithm I will follow this list:

* Model the optimization problem using classes and function. The purpose of this is to abstract things.
  - The point is to make simplify stuff like: calculating the derivatives, wrap the objective function, etc.
* Implements the two Algorithms (SMO and DCD). They need a differ formulation of the problem.
* Choose a small dataset from [here](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/) to use as a test.
* Verify if they generate a comparable result with LinearSVC.
* Choose some (3 or 4) dataset of increasing dimension to validate the result about complexity.
* Change the threshold used to stop the algorithm and see what happens.
* Maybe, get a very large dataset and create artificial ones with increasing dimension to plot a more accurate curve.
* Allocate to the algorithm the same time, and see at what accuracy they can reach.
* Write the conclusions


## How to RUN this project

After downloading the project from GitHub, the necessary dependencies to run it are:
* matplotlib
* scikit-learn
* numpy
* jupyter
* pandas

To install everything need fast I used **conda** with this command:
```
conda create --name OPT numpy scikit-learn jupyter conda-forge::matplotlib pandas
```

To run the notebook is sufficient to run:
```
conda activate OPT
jupyter lab
```
More on the code inside the notebook.
