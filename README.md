# Optimization Methods Project Work: SMO and DCD-Linear for SVMs

TODO (Brief introduction of what I'am doing)
## Goal of the Project

TODO

## What to achive

To confront the two algoritm I will follow this list:

- [ ] Model the optimization problem using classes and function. The purpose of this is to abstract things.
 - The point is to make simplify stuff like: calculating the derivatives, wrap the objective function, etc.
- [ ] Implements the two Algorithms (SMO and DCD). They need a differ formulation of the problem.
- [ ] Choose a small dataset from [here](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/) to use as a test.
- [ ] Verify if they generates a comparible result with LinearSV and SVC from scikit-learn.
- [ ] Choose some (3 or 4) dataset fo increasing dimension to validate the result about complexity.
- [ ] Change the threshold used to stop the algorithm and see what happends.
- [ ] On every experiment measure loss (and maybe validation) and see how they perform.
- [ ] Maybe, get a very large dataset and create artifical ones with increasing dimension to plot a more accurate curve.
- [ ] Write the conclusions


## How to RUN this project

After downloading the project from GitHub, the necessary dependancies to run it are:
* matplotlib
* scikit-learn
* numpy
* jupyter
* pandas

To install evryting need fast I used **conda** with this command:
```
conda create --name OPT numpy scikit-learn jupyter conda-forge::matplotlib pandas
```

To run the notebook is sufficent to run:
```
conda activate OPT
jupyter lab
```
More on the code inside the notebook.
