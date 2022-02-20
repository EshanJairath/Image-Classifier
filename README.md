# Image-Classifier
Image classifiaction done on cifar 10 using deep learning (CNN)

In this Repository there are 3 CNN models that are trained on Cifar-10 dataset and all three of them gives diffrerent accuracy in increasing order.
The models were tested to predict one image of every category in the CIFAR-10 all models in this study properly predicted the images , although the class probabilities were different. 
The random images of every category that were used to test the prediction of every model in this study are in the sample images Folder.

In the Case of Model 1 - 
The accuracy is 78% on validation data using Adam optimizer 

In the Case of Model 2 - 
The accuracy is 82% on validation data using SGD

In the Case of Model 3 - 
The accuracy is 86% on validation data using SGD 

It is clearly visible that changing the optimizer in the case of model 1 affected the accuracy as adam optimizer was able to get higher accuracy. 
Introduction of data augmentation in the case of model 2 and using test set directly for the  validation resulted in 2% increase in accuracy on SGD 
optimizer which outperformed Adam and resulted in 4% boost in accuracy from the initial model 1. 
When Batch normalization layers were added after every convolution layers in the case of model 3, the model showed huge 8% jump in validation accuracy, 
when compared to initial model.   Models 2 and 3 predicted all the images of every category correctly with possibilities in increasing order as per model.
The initial model with lowest accuracy made one incorrect prediction and gave low possibilities of every category when compared to model 2 and 3.

