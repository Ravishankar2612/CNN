Project Overview - To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

##Table of contents
* [General Info](#general-information)
* [Library Used](#library-used)
* [Conclusions](#conclusions)
* [Technology](#Technology)

## General Information.
 - The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant . To perform augumentation and build a model to predict the cancer images.

## Library used
 - Pandas
 - Tensor Flow
 - Keras
 - Seaborn
 - numpy
 - matplot
 


## Conclusions

# Model 1 : 
Observation :

Train accuracy = 0.82

Validation accuracy = 0.53

val loss = 2.16

loss = 0.49

There is a significant difference between validation and train accuracy this shows model has overfitted

We Need to choose right augumented strategy as the data has more class imbalance

# Model 2 :

loss: 1.09 accuracy: 0.59

val_loss: 1.3182

val_accuracy: 1.3

Here we can see that there is not that much difference between Val loss and training loss. Loss values are close.

It's not showing overfitting but accuracy is low. Need to improve accuracy. That's why we should generate more artificial data.

# Model 3 :

loss: 0.58 accuracy: 0.78 val_loss: 0.82 val_accuracy: 0.71 Now we got good accuracy for both Training and validation data.

Now all the issues are resolved like overfitting and low accuracy.

We can consider this as final model.

## Technology
 - library - version 3.0

## Contact
Created by [Ravishankar2612] - feel free to contact me!

