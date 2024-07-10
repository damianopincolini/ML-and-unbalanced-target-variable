# ML-and-unbalanced-target-variable
How to treat a dataset with an unbalanced dicotomic target variable using both under and oversampling and optimizing the ratio between the two possible classes of the outcome.

This project aims to define a machine learning model able to solve a classification problem. Starting from a dataset containing features about a direct marketing campaigns (phone calls) of a Portuguese bank (Moro,S., Rita,P., and Cortez,P.. (2012). Bank Marketing. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306), the goal is to predict if the client will subscribe a term deposit.

My specific interest will not be to find the best model based on a specific performance metric; instead, given a model, I want to tune its parameters in a proper way and, above all, handling the unbalanced distribution of the binary target variable ("yes", "no").

My attempt will be to proper evaluate how to fix the unbalanced distribution and, specifically, what between an undersampling or an oversampling strategy will fit the bill better.

I will download the dataset, wrangle it (for what necessary) and split into training and test set.

I will run explorative data analysis only on training set, so to avoid any data leakage and will take into account the results of this analysis to set a proprer pre-processing recipe.

During preprocessing, I will "re-balance" the target variable distribution via both undersampling and oversampling using different ratio between the two target classes and I will train a decision tree model (so to rank variable importance).

Finally, I will check what solution will produce the best result.


This repository contains the orginal dataset (.csv), the quarto file containing the code chuncks and the final report in .pdf format. 
