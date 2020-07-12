# Udacity Deep Learning Nanodegree  

## Dog Breed Classifier

### Table Of Contents

1. Installations
2. Project Motivation
3. Project Overview
4. File Descripton
5. Acknowledgement
6. Authors


### Installations

* numpy
* glob
* matplotlib
* torch
* cv2
* torchvision
* pqdm
* PIL
* jupyter lab


### Project Motivation

This project aims at classifing the dog breeds based on images given to it. 
It first successfully detect the human faces and the dog faces from the images.
Then it uses a pre-trained VGG16 Net to find the predicted class for a given image.

## Project Overview

In this project, Given an image of a dog, my algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.


## File Description

* dog_app.ipynb

   Contains main code

* README.md

* haarcascades
    Conatins xml file, that helps in predicting the faces of humans
    
* REPORT.html
    It is the html file of dog_app.ipynb
    
* images
    It contains all the images that the network used to train.

* Data 
   This folder contains all the data for the training purpose
   ** Downloading Dataset **
   	To download the Dog dataset
   	Click [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip) to download
	To download the Human dataset
	Click [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip) to download


## Acknowledge

Besides, you must know that the project is under the Udacity Deep Learning Nanodegree.


## Authors

* **Goutam Kumar Ghadai**
* **email - goutam.ghadai2199@gmail.com**
