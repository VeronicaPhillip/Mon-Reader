# Mon-Reader

# Data Science Project

The objective of the project was to predict using a simple image from smart phones videos whether a page is being flipped using a single image.

# Background and Problem Statement

The company develops innovative Artificial Intelligence and Computer Vision solutions that revolutionize industries. The devices can recognize faces, estimate age and gender, classify clothing types and colours, identify everyday objects, and detect motion. 

Mon Reader is a new mobile document digitization experience for the blind, for researchers and for everyone else in need for fully automatic, highly fast, and high-quality document scanning in bulk. It is composed of a mobile app and all the user needs to do is flip pages and everything is handled by Mon Reader: it detects page flips from low-resolution camera preview and takes a high-resolution picture of the document, recognizing its corners and crops it accordingly, and it uses the cropped document to obtain a bird's eye view, sharpens the contrast between the text and the background and finally recognizes the text with formatting kept intact, being further corrected by Mon Reader’s ML powered redactor.

We are tasked with predicting from video images collected, whether a page will be flipped or not.

# Project overview

The project was carried out using data collected from smart phone videos which were labelled as ‘flip’ and ‘notflip’.

We will use classification techniques to determine the class of the data and the likelihood of the occurrence.

The data consists of 


The goal of the project is to predict if the page is being flipped using a single image.

The success metrics that will be used to evaluate model performance will be F1 score, the higher the better.

In this project python was used to build predictive models. Deep learning techniques were used to determine whether a page would be flipped or not from smart phone video images collected. Torchvision a   Convolutional Neural Network (CNN) model was used to determine whether a flip would occur or not. 

# Prerequisites

To run the code, there were a number of Python and torch vision libraries that needed to be installed. These are as follows:

*	Pandas
*	NumPy
*	Matplotlib
* Seaborn
*	Tensorflow
*	Torch
*	Torchvision


# Summary/Findings
Using the F1 Score as the metrics the best performing model is achieved using Epoch 3, which gives a score of 99% with a training loss of 6.8%.
![image.jpg](attachment:image.jpg)
 
The model is a high performing model with a relatively high performance and so could be relied on to give very good results.


