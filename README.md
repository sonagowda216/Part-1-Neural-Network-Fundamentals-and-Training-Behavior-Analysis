# Part 1: Neural Network Fundamentals and Training Behavior Analysis

## Overview
Build and analyze a feed-forward neural network to predict customer churn (binary classification).

## Dataset
customer_churn_nn.csv — Customer account and usage features. Target: churn (1=churned, 0=retained).

## Folder Structure
```
part-1-neural-network-analysis/
├── README.md
├── notebook.ipynb
├── requirements.txt
└── results/
    ├── model_comparison_table.csv
    └── evaluation_outputs.png
```

## Tasks
1. Dataset Understanding — exploration, feature types, missing values, target distribution
2. Data Preprocessing — imputation, encoding, scaling, train-test split
3. Neural Network Model Building — feed-forward NN (TensorFlow/Keras)
4. Training and Evaluation — accuracy, loss, confusion matrix
5. Hyperparameter Experimentation — 3 configs compared in a table
6. Final Reflection — weights, activation functions, learning rate, overfitting

## How to Run
```
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```
