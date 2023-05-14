# 12th-place-solution-Turtle-Recall-Conservation-Challenge
## Approach
The Turtle Recall: Conservation Challenge Solution was built on an optimized cross validated ensembled CNN tranfer learning models that was averaged to give the result
## Data Types:
Input data consists of a set of labelled JPG images of turtle faces from three different perspectives: top, left, right. There are 100 distinct turtle identities present in the training set.
An additional set of labelled images has also been provided. This set does not contain information about the position of the turtle’s face captured, but you may still find it useful.Some test images correspond to turtles in the training dataset and others do not.

For a given query image, return either the identity of the turtle in the image (as specified in the training data labels) or return the ‘new_turtle’ label.

## Model Training and Prediction:
The algorithm used was a CNN transfer learnin models (VGG16,ResNet101V2,ResNet50,Xception ...) The model was then trained using a 5-fold cross-validation, and predictions made on the test set with each fold. The final prediction was an average of predictions from every fold.

link to the competition: https://zindi.africa/competitions/turtle-recall-conservation-challenge/
