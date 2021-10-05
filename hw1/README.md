# Homework 1 Report

1. Created a simple model to train on the stanford car images dataset from kaggle https://www.kaggle.com/jutrera/stanford-car-dataset-by-classes-folder
2. 1st model: A basic model with 4 convolutional layers and maxpoolinglayers, it is flattened at the end with 2 dense layers and a softmax activation function.
  a. This model trained poorly and is overfitting a lot
  b. final validation accuracy is 0.0307 and final training accuracy is 0.9968
3. 2nd model: Added dropout layers to the first model to combat overfitting
  a. improved validation accuracy
  b. final validation accuracy is 0.0405 and final training accuracy is 0.9982
4. 3rd Model: Added L2 regularizers to the 2nd model to combat overfitting
  a. improved the validation accuracy even further
  b. final validation accuracy is 0.0479 and final training accuracy is 0.9969
  
# Inferences:
1. The base model might be too basic to train such a extensive dataset which resulted in overfitting by a lot. In the future, I will utilize more famous and popular models such as     Resnet50 or MobilenetV2.
2. Adding dropout layers and using regularization techniques will reduce overfitting. This is because they will ignore the noise the dataset might have and train meaningful data instead.
