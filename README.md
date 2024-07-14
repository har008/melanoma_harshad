# Melanoma Detection
The task is to detect type of skin cancer for a given image using Convolutional Neural Networks.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- It is an multicalss image classification problem having 9 different classes.
- We have a data set having skin cancer images having 9 type of skin cancers.
- We want to use the Neural Networks to detect the chances of skin cancer which can reduce the manual efforts needed for it's diagnosis. 
- We are using Melanoma dataset with train and test sets havin 2239 and 118 images respectively


## Conclusions
- Initially when I used the CNN model on original data having 2239 images the model overfit on the training data and validation accurcy very low.
- Then after using data augmentation technique, Overfitting condition has been resolved but the accuracies for both training and validation didn't improve
- Image Augmentaion - Adding new augmented images to the data drastically improve the accuracies, but there was still a bit of overfitting condition.



## Technologies Used
- matplotlib == 3.7.5
- numpy == 1.26.4
- pandas == 2.2.2
- tensorflow == 2.15.0
