# Machine_Learning
 Machine Learning project 2021/2022

Data Science and Business Informatics - University of Pisa

A. Carnevale, F. Canepuzzi, G. Segurini

## Introduction
For this project it is required to solve a regression task on the CUP dataset. It is focused on
trying out the different models, selecting the best hyperparameters configuration and compare
their performances. We used: KNN, SVM, LBE, Random Forest and Neural Network. These
models were first used to perform a classification task on the well-known MONK dataset as
a benchmark. Finally, we implemented from scratch a Stacking and a Voting ensemble by
combining the tuned estimators above.

## Simple models results
Performance of the models evaluated with a Crossvalidated approach

<img
  src="/Images/single_models.png"
  width=50%>

## Ensemble models results

Performance of the ensembles using as base estimators a subset of the models above

<img
  src="/Images/ensemble_models.png"
  width=50%>
