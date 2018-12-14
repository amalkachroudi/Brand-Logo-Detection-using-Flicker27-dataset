# Brand-Logo-Detection-using-Flicker27-dataset
This is a Brand logo classification done by convolutional  network based on TFLeanrn and python.
The dataset is taken from flickr 27 logo dataset.

# Steps
Inorder to train the convolutional network  and classify the data set:
* Preprocese the images and split the data into train and test sets.
* Index the data into a pickle file which contains features of the logo such as width, height and no. of channel.
* Increase the dataset size by doing image augmentation (rotation, shiftting,..).
* As now we have the pickle file, we can train the neural nets using TFLearn.

