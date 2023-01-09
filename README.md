# Diabetes Prediction - Ensemble Model

## Predict the onset of diabetes based on diagnostic measures

The main objective is to predict whether the people in the dataset have diabetes. Because in this example we focused on improving the accuracy of our prediction, we used an ensemble method – Voting Classifier – to combine the results of the base models. Two of the base models we have used are also ensemble models. We have used two versions of Voting Classifiers – with and without weights.

* Training and test data from https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database.
* The ensemble approach has been proposed using a soft voting classifier to classify diabetes. 
###	Used VotingClassifier,KNeighborsClassifier and SVC Hyperparameter tuning to increase the accuracy. Accuracy achieved is 77%. 
