A comprehensible Classical Machine Learning model will be used to predict as accurate as possible a classification problem.
For the prediction to be as accurate as possible, I've initially used the feature selection methods and reduced the number of features to the 6 most relevant ones.

Later on, I've developed modeling and inference using cross-validation to train and evaluate the models with the accuracy metric. The best performers were NB, SVM and LR. Since NB has very limited hyperparameters, the optimization should be done by tweaking other phases of the analysis, which was not done in this project due to the short amount of time available.

The hyperparameters optimization was performed to see if there was room for some more improvement. SVM did not show improvement and LR did display higher performance on normalized data, if compared to the previous result. Therefore, LR was chosen for implementation.

Through the test set, the achieved accuracy of 81.03 for LR was not as high as expected but still within the good metric threshold.

At last, a prediction on the application of the model on unseen data was carried out, considering three new instances. Those instances returned consistent output results, which have taken into account the presence or absence of heart disease in individuals / patients.

