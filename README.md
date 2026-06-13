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




The accuracy of the custom implementation of model is 0.8819.
The precision of the custom implementation of model is 0.8855.
The recall of the custom implementation of model is 0.8819.
Results for custom softmax regressor : 
https://colab.research.google.com/drive/14vfkIyaml22RkG2vo7oNFjqoK20veEjA#scrollTo=z_OYcvLf-5N4&fullscreenOutput=true




The accuracy of the sklearn model is 0.9518.
The precision of the sklearn model is 0.9529.
The recall of the sklearn model is 0.9518.
Results for sklearn softmax regressor :
https://colab.research.google.com/drive/14vfkIyaml22RkG2vo7oNFjqoK20veEjA#scrollTo=tg3GeZId-5N-&fullscreenOutput=true



