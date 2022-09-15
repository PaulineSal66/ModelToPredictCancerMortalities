# Model to predict cancer mortalities (inference statistics)

This project has been done in a context of Advanced Stat class at Data ScienceTech Institute.

## Project
The data used for this project is cancer_reg.csv file that you can load thanks to the
URL :
https://data.world/exercises/linear-regression-exercise-1/workspace/file?filename=cancer_reg.csv



## Goal
The goal is to find the best model to predict cancer mortalities (target_deathrate).

For that, here is the strategy used:
1) Preprocessing of the data (handling missing values, description of the variables of the dataset)
2) Performing an ordinary least square model to explain the target_deathrate variable thanks to the numerical ones.
3) Selection of variables by using a step by step method at first and a penalized one
then.
4) Performing a CART algorithm, and identification thanks to VSURF the subset of interested variables and use this subset to construct a
CART tree.
5) Conclusion concerning the best model?
