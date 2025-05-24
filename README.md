# Holiday-Package-Prediction

The use case is to predict the customers who will avail the list of holiday packages that are available.

As it is a classification use case, we will be using classification algorithms like Logistic Regression, Decision Tree Classifier & Random Forest Classifier.

Post the model training & hyper parameter tuning using Grid Search CV, we see that Decision Tree Classifier best suits for this use case based on the reports
of evaluation metrics like Accuracy Score, Precision, Recall, F1 Score, Confusion Matrix (Type I/Type II Errors), ROC-AUC score.

The recall should be as high as possible when compared to Precision. This is because Type II Error (FN) should be as low as possible.