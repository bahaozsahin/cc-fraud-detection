<!--<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script> -->



## Project definition:
The project aims to predict credit card fraud cases using machine learning algorithms.


<br>

## Dataset:
The dataset consists of 5626 rows of data with 50 independent variables, 1 target column, and 1 index key. It is important to note that the data is highly imbalanced, meaning that the number of fraudulent cases is significantly lower than the number of non-fraudulent cases.

## Goal:
The goal of this project is to develop a predictive model that can accurately classify credit card transactions as either fraudulent (1) or non-fraudulent (0).

## Evaluation metrics:
To evaluate the performance of the predictive model, the following metrics will be used:


1. $$\frac{\text{Recall (0)}}{\text{Recall (1)}} \leq 0.025$$

2. $$\left(\frac{\text{Recall (0)} + \text{Recall (1)}}{2}\right) \geq 0.75$$
These evaluation metrics will provide insights into the model's performance in terms of correctly identifying fraud cases while maintaining a balance between accuracy and recall across both classes.
