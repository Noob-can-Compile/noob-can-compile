---
layout: post
title: "Automatic Image Captioning with CNN & RNN"    
author: krunal kshirsagar
---
## A Pytorch implementation of the CNN+RNN architecture on MS-COCO dataset.

# Overview: 
Generally, a captioning model is a combination of two separate architecture that is CNN (Convolutional Neural Networks)& RNN (Recurrent Neural Networks) and in this case LSTM (Long Short Term Memory), which is a special kind of RNN that includes a memory cell, in order to maintain the information for a longer period of time. Basically, CNN is used to generate feature vectors from the spatial data in the images and the vectors are fed through the fully connected linear layer into the RNN architecture in order to generate the sequential data or sequence of words that in the end generate description of an image by applying various image processing techniques to find the patterns in an image.
