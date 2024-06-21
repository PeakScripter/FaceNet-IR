# Face Recognition using PyTorch

Face recognition is the ability to look at the digital image of a human and recognize the person just by looking at the face.

FaceNet was introduced in 2015 by Google researchers; it has been a backbone of many open source Face Recognition networks like OpenFace.
It is a one shot learning method that uses a Deep Convolutional Network to directly optimize the embeddings.
The network consists of a batch input layer and a deep CNN followed by L2 normalization, which results in the face embedding. 
This is followed by the triplet loss during training.

![FaceNet Training](uploads/FaceNet.jpg)

It returns a 512 dimensional vector face embeddings for each face. 

## Description

A facial recognition system is a technology capable of identifying or verifying a person from a digital image or a video frame from a video source. There are multiples methods in which facial recognition systems work, but in general, they work by comparing selected facial features from given image with faces within a dataset. 

This FaceNet model uses both the Inception architecture and Resnet architecture.
