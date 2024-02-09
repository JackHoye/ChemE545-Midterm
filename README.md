Mission of the product is to train a machine learning model to predict the biodegradability of a plastic/material using information extracted from its SMILES string.
Portion (1) of the enclosed Jupyter Notebook imports the data from the Harvard Clean Energy Project DataBase (HCEPD) and extracts/saves information from the SMILES.
Portion (2) will train a simple linear regression ML model and test its accuracy.
Portion (3) uses similar architecture to train a polynomial regression model.

Work was completed as a team with Olivia Dotson managing portion (1), Christina Yang managing portion (2), and Jack Hoye managing portion (3).

Original data set was sourced from the Harvard Clean Energy Project Database (HCEPDB), which has not been included in this repository to maintain their integrity.
Part (a) requires data preparation and reformating to implement linear regression based machine learning, as well as a non-linear regressor (we implemented polynomial regression)
Data prep was handled by Olivia Dotson, regression was managed by Christina Yang requires a non-linear regression model was implemented. Polynomial regression was chosen
Jack Hoye and Christina Yang implemented the polynomial regression
Part (b) requires implementation of a classification model
Christina Yang implemented to classification task
Part (c) requires implementation of a logistic regression task
Jack Hoye handled the logistic regression and Newton-Cholseky method, as well as plotting the confusion matrix and ROC plot
