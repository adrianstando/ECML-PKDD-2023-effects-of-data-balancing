# Explainable imbalanceD learninG compARatOr

## Overview

The usage of many balancing methods like Random Undersampling, Random Oversampling, SMOTE, NearMiss is a very popular 
solution when dealing with imbalanced data. However, a question can be posed of whether these techniques can change the
model behaviour or the relationships present in data. 

As there are many kinds of Machine Learning models, this package provides model-agnostic tools to investigate the model
behaviour and its changes. These tools are also known as Explainable Artificial Intelligence (XAI) tools and include
techniques such as Partial Dependence Profile (PDP), Accumulated Local Effects (ALE) and Variable Importance (VI). 

Apart from that, the package implements novel methods to compare the explanations, which are *Standard Deviation of 
Distances* (for PDP and ALE) and the Wilcoxon statistical test (for VI).

Generally speaking, this package aims to giving a user-friendly interface to investigate whether the described 
phenomena take place.

The package was written in Python and consists of four modules: *dataset*, *balancing*, *model* and *explain*. 
It provides a simple and user-friendly interface which aims to automate the process of data balancing with different 
methods, training Machine Learning models and calculating PDP/ALE/VI explanations. The package can be used for one input
dataset or for a number of datasets arranged in arrays or nested arrays.

## Technologies

The package was written in Python and was checked to be compatible with Python 3.8, Python 3.9 and Python 3.10.

It uses most popular libraries for Machine Learning in Python:

* pandas, NumPy
* scikit-learn, xgboost
* imbalanced-learn
* dalex
* scipy, statsmodels
* matplotlib
* openml

## Installation

The `edgaro` package can be installed by:

```console
pip install -e ./
```


