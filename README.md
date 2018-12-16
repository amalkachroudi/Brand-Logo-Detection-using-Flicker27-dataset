
# Brand-Logo-Detection-using-Flicker27-dataset
This is a Brand logo classification done by convolutional  network based on TFLearn and python. The dataset is taken from flickr 27 logo dataset.

The Flickr logos 27 dataset is an annotated logo dataset downloaded from Flickr. It involves three image sets:

* The training set contains 810 annotated images, corresponding 27 logo classes (30 images for each class). There is actually one picture missing so we have 809 images.
* The distractor set contains 4207 logo images outside of the 27 classes. We ignore this image set in our experiment.
* Finally, the query set consists of 270 images, of which 135 are for each of the 27 annotated classes. The rest 135 images do not depict any logo class, and we ignore these images.

The brands included in the dataset are: Adidas, Apple, BMW, Citroen, Coca Cola, DHL, Fedex, Ferrari, Ford, Google, Heineken, HP, McDonalds, Mini, Nbc, Nike, Pepsi, Porsche, Puma, Red Bull, Sprite, Starbucks, Intel, Texaco, Unisef, Vodafone and Yahoo.

Here are sample images in the training and query (or test) set.

Sample images in training set 

![myimage-alt-tag](https://shuaiw.github.io/assets/deep-learning-for-logo-recognition/flickr27-train.jpg)

Sample images in query set 

![myimage-alt-tag](https://shuaiw.github.io/assets/deep-learning-for-logo-recognition/flickr27-test.png)


## Steps

In order to train the convolutional network  and classify the data set:
* Preprocese the images and split the data into train and test sets.
* Index the data into a pickle file which contains features of the logo such as width, height and no. of channel.
* Increase the dataset size by doing image augmentation (rotation, shiftting,..).
* As now we have the pickle file, we can train the neural nets using TFLearn.

