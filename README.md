# 🧬 Genetic Algorithm for Feature Selection

This project implements a Genetic Algorithm (GA) to perform feature selection on the Breast Cancer dataset from scikit-learn. The aim is to improve model performance and reduce complexity by selecting only the most important features.

## 🚀 Features

Implements a genetic algorithm to select optimal feature subsets

Uses Random Forest as the classifier to evaluate fitness (accuracy)


Visualizes:

Accuracy improvement over generations

Accuracy before vs after feature selection

Execution time before vs after feature selection

Compares model performance on full vs selected features


## 📊 Dataset

The model uses the built-in Breast Cancer Wisconsin Diagnostic Dataset from sklearn.datasets.

## 🧪 How It Works
Initialization: A population of binary chromosomes is created. Each gene represents whether a feature is selected (1) or not (0).

Fitness Evaluation: For each chromosome, a Random Forest classifier is trained using the selected features and accuracy is calculated.

Selection: Parents are selected probabilistically based on fitness.

Crossover & Mutation: Children are generated using single-point crossover and mutation.

Evolution: The process is repeated for a number of generations.

## 📈 Results
Outputs selected features per generation

Plots the accuracy progression across generations

Compares model performance (accuracy & time) before and after feature selection
