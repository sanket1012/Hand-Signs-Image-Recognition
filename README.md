# Hand Signs Image Recognition

In this project I have build a neural network using tensorflow.  

The dataset consists of :  
**Training set:** 1080 pictures (64 by 64 pixels) of signs representing numbers from 0 to 5 (180 pictures per number)  
**Test set:** 120 pictures (64 by 64 pixels) of signs representing numbers from 0 to 5 (20 pictures per number)

**Model:** *LINEAR -> RELU -> LINEAR -> RELU -> LINEAR -> SOFTMAX*. The SIGMOID output layer has been converted to a SOFTMAX. A SOFTMAX layer generalizes SIGMOID to when there are more than two classes. 

**Goal:** To build an algorithm capable of recognizing a sign with high accuracy using a tensorflow model and a softmax output.
