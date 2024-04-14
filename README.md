# INTRABHAWAN ML COMPETITION
# IMAGE CLASSIFICATION USING CNN

First we imported all needed libraries
Then we imported the dataset
We split the dataset into train,validation and test dataset using splitfolder library
We use data augmentation layer using randomflip,randomrotation and randomzoom

Firstly we trained the dataset using basic cnn consisting of conv2D and maxpooloing layers but the model underperformed giving us around 83% training accuracy and 78% validation accuracy
Then we studied about VGG16 and RESNET50 transfer learning models.RESNET50 gave a better accuracy so we used it for our model with dense layer of 512 units
Finally it gave a training accuracy of 98.98% and validation accuracy of 95.22% after 10 epochs(Training loss of 0.0293 and validation loss of 0.1856)

We used the Adam optimizer and sparse_categorical_crossentropy for computing loss function

We fot 95.85% accuracy in Test dataset
