# Dog-Breed-Classifier

# Overview

The goal of this project if a dog is detected in the image, return the predicted breed.

Our end project goal is to create a model which does the following:  

<ul> if a dog is detected in the image, return the predicted breed.  </ul>
<ul> if a human is detected in the image, return the resembling dog breed. </ul>
<ul> if neither is detected in the image, provide output that indicates an error. </ul>

# Dataset

The data sets can be downloaded here:

1. [Download the dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
2. [Download the human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)

# Files

Jupyter Notebook - The full code is contained in the notebook dog_app.ipynb in this github repository.

Blog - I have also written an article in medium which can be accessed [here](https://medium.com/@moumita_30467/identifying-dog-breeds-using-deep-learning-7fcc4854aad3).

Folders - images and my_images folder contains images that I haved used for testing. 

The haarcascades folder holds the xml file for use with the OpenCV face detector class that is used in the notebook.

# Technologies Used

Python and its libraries, Pytorch for CNN, OpenCV, VGG-16 as pretrained model and resnet50, opencv-python
jupyter, matplotlib, pandas, numpy, pillow, scipy, tqdm, scikit-learn, scikit-image, seaborn, h5py, ipykernel, pickleshare

# Summary

The CNN model from scratch yielded an accuracy of 18%, well above the 10% target and the final model using transfer learning with the pretrained model Densenet121 produced 84% accuracy in identifying dog breeds.

# Acknowledgement

Thank you Udacity for providing the opportunity to work on this project!
