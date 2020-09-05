# DL_CNN-Projects
This repository contains project files based on CNN.
The first project added here is:
Brain Tumor Detection:
database link :- https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection

This data contains total 253 images where 98 are normal brain mri images and 155 images which has tumor.
task is to classifiy these images.

Steps for classification:
1) Data Augmentation:
As the data set is less we need to add more images to our data, this is achieved by "ImageDataGenerator" which is a part of "tensorflow.keras.preprocessing.image" import

2) Preprocessing :
Removed the excess part of the image applied thresholding and performed image opening and found image Contours.

3) Data visualization:
The two class data is visualized with the help of "matplotlib".


4) Model creation and visualize results:
Used a convolution and maxpooling layers and as the output is binary used "Sigmoid" activation at the output layer.

