# Session 4: Supervised Machine Learning. 

## Steps to train a model: 
1. Data collection and processing.
2. Division of training data in Train and Test sets.
3. Use the train set to train the model.
4. Predict an output for the test set and compare the predicted vs real results.
5. Improve the model until we are satisfied with the performance on the test set 

## Types of supervised ML models 

- Classification: Classification problems are characterized by having categorical output (i.e: active, inactive), so the model tries to predict to which class the input belongs. It can include several classes, is not limited to a binary classification. 
- Regression: Regression problems are characterized by continuous variables, where the model tries to predict the exact value of the input (i.e: IC50 of a specific compound)

### Evaluation of supervised ML models 

Classification metrics: We obtain the following data to evaluate the model: 
  - Y_pred: predictions on the test set 
  - Y_real: real outcome of the test set 
- Accuracy: number of correct predictions divided by the total number of predictions (TP/(lenY)). For example, if we have predicted correctly 5 out of 10 data points --> Accuracy = 50%
- Precision: identification of only real positives (with a 100% precision, a model does not classify any negatives as positive) --> TP/(TP+FP) 
- Recall: identification of all positives (with a 100% recall, no positive is classified as negative, but some negatives might be included in the positives) --> TP / (TP+FN) 
- Confusion matrix: plots the real vs the predicted values in a table, to easily obtain the FP, TP, TN, FN values. 

Regression metrics: In a regression task, we obtain as error the difference between the predicted value and the real value (i.e: IC50real=0.1, IC50pred = 0.5 --> error of 0.4). 
- Mean Absolute Error: mean of the absolute values of errors. 
- Mean Squared Error: mean of the square error. By squaring, larger errors are contributing more and therefore the model punishes them. 
- Root Mean Squared Error: root of the mean of square error to simplify interpretation (by using MSE, we also square the units which makes them difficult to interpret). 
- R-square: coefficient of determination, the amount of variance explained by the model (from 0 to 1, the closer to 1, the better our model is)

### Sklearn package
Sklearn package is a popular Python package for machine learning. It contains algorithms for machine learning techniques like classification, regression and clustering.
