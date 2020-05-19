# Data Understanding

Target variable to predict is isup_grade, which is severity of cancer on a 0-5 scale. \
Each image is stored in large .tiff file 

## Train images
1. Which part of image is responsible for isup_grade is present in segmentation masks.
2. Not all images have the segmentation masks, and wherever present it can be a false positive or false negative.
3. Masks can be used to develop ways to select sub-samples from images. 
4. Mask value is different for different data provider. Radound (0-5) and Karolinska (0-2)

## Test Set
Test set contains 1000 images

1. Some of training images have pen marks but test set is free of them.
2. 
