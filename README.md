# Mice Behavior Prediction Based on Protein Expression Data

## Project Overview

This project applies various statistical methods to predict mice behavior based on protein expression data. The dataset consists of protein expression levels from control and trisomic mice, with the goal of analyzing the relationship between protein expressions and behavior. The project employs techniques like Mann-Whitney test, ANOVA, regression models (Logistic, Ridge, and Polynomial), and feature selection methods to achieve 100% accuracy in behavior prediction.

## Methodology

### 1. **Mann-Whitney Test**
Used for comparing differences between two independent groups to see if they belong to the same population.

### 2. **Kruskal-Wallis Test**
A generalization of Mann-Whitney used to determine differences between more than two independent groups.

### 3. **Nemenyi Test**
Post-hoc test to identify which pairs of groups differ after Kruskal-Wallis.

### 4. **Chi-Square Test of Independence**
Determines if there is an association between two categorical variables.

### 5. **Forward and Backward Stepwise Selection**
Methods for feature selection to identify the most important predictors.

### 6. **Logistic Regression**
Predicts binary outcomes based on protein expression data.

### 7. **Ridge Regression**
Applied when predictor variables are highly correlated.

### 8. **Polynomial Regression**
Used to model nonlinear relationships between variables.

## Data Description

The dataset contains protein expression data for 77 proteins, measured in 72 mice (38 control, 34 trisomic), with 15 measurements per protein for each mouse. The data is used to predict whether mice are stimulated to learn (context-shock) based on protein expression levels. Key features include:

- **Genotype**: Control or trisomic.
- **Behavior**: Mice either stimulated to learn or not.
- **Treatment**: Mice either treated with memantine or not.

The final dataset contains 1080 total measurements and focuses on the top 20 proteins to predict behavior.

## Results

- **Model Accuracy**: Achieved 100% accuracy with Logistic and Polynomial Regression models.
- **Ridge Regression**: Achieved 85.3% accuracy.
- **Statistical Analysis**: The tests and regressions demonstrated significant insights into the relationship between protein expressions and behavior, contributing to the understanding of factors affecting mice behavior.

## Conclusion

This project demonstrates the successful use of statistical methods to predict behavior based on protein expression data, offering insights into genetic and treatment-based factors influencing mice behavior. The models can be extended to similar biological prediction tasks and contribute to studies on behavior modification and treatment efficacy in genetically modified organisms.
