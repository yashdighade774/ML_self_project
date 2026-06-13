# ML_self_project
I made this self project of machine learning involving scratch implementation of two powerful machine learning models.First one being PCA and the second one was Softmax regressor.

For dimensionality reduction using PCA I have derived the number of features to which total 561 features of Human activity recognition dataset will be reduced using explained variance ratio.I found that the newly transformed 34 features captures 90 percent variance of the data i.e. they explain 90 percent information.

For training process I have divided the training data into training and validation data 80/20.I have done One hot encoding of target getting 6 columns representing 6 classes of target.

I have plot training and validation errors on matplotlib and along with that I have compared accuracy ,precision and recall of custom and sklearn's implementation of softmax regressor.

Number of training samples : 7352
Number of testing samples : 2947
Number of Features initially : 561
Number of features after dimensionality reduction : 34
Number of target columns : 6
Names of target features : ['LAYING','SITTING','STANDING','WALKING','WALKING_DOWNSTAIRS','WALKING_UPSTAIRS']



Classification report of custom softmax regressor
              precision    recall  f1-score   support

           0       1.00      1.00      1.00       537
           1       0.85      0.72      0.78       491
           2       0.78      0.88      0.83       532
           3       0.85      0.97      0.91       496
           4       0.94      0.78      0.85       420
           5       0.90      0.91      0.90       471

    accuracy                           0.88      2947
   macro avg       0.89      0.88      0.88      2947
weighted avg       0.89      0.88      0.88      2947


The accuracy of the custom implementation of model is 0.8819
The precision of the custom implementation of model is 0.8855
The recall of the custom implementation of model is 0.8819











Classification report of sklearn model
              precision    recall  f1-score   support

           0       0.99      1.00      0.99       537
           1       0.96      0.88      0.91       491
           2       0.90      0.96      0.93       532
           3       0.93      1.00      0.96       496
           4       0.97      0.95      0.96       420
           5       0.98      0.92      0.94       471

    accuracy                          0.95      2947
   macro avg       0.95      0.95      0.95      2947
weighted avg       0.95      0.95      0.95      2947

The accuracy of the sklearn model is 0.9518
The precision of the sklearn model is 0.9529
The recall of the sklearn model is 0.9518
   macro avg       0.89      0.88      0.88      2947
weighted avg       0.89      0.88      0.88      2947
