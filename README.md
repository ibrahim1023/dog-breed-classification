# Dog Breed Identification (Classification)
This project provides a solution to Kaggle's [Dog Breed Identification Challenge](https://www.kaggle.com/c/dog-breed-identification). 

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Dataset](#dataset)
* [Features](#features)
* [Models](#models)
* [Graphs](#graphs)
* [Dependencies](#dependencies)

## General info 
The project takes a pretrained model from TensorFlowHub to train and evaluate the model using images of the various breeds of dogs.

## Technologies
* Python
* Anaconda-Navigator 
* Kaggle API

## Setup
* Download Python: https://www.python.org/downloads/
* Download Anaconda-Navigator: https://www.anaconda.com/products/individual
* Setup Kaggle API: https://github.com/Kaggle/kaggle-api

**Note**: Make sure to setup the kaggle-api as you'll require the kaggle.json file in order to use the jupyter notebook

## Dataset
The data is provided by the competition that contains 10,000+ images for training and testing. An image can be classified as one of the 120 breeds (labels). 

### Features
Each image has a filename that is its unique id. The dataset comprises 120 breeds of dogs like:

| Breeds | 
| :---  | 
| `affenpinscher` | 
| `afghan_hound` | 
| `african_hunting_dog` |
| `airedale` | 
| `american_staffordshire_terrier` | 
| `appenzeller` |
| `australian_terrier` |

![Image-1](https://github.com/ibrahim1023/dog-breed-classification/blob/main/preview_images/image-1.jpg?raw=true "Data Preview")

![Image-2](https://github.com/ibrahim1023/dog-breed-classification/blob/main/preview_images/image-2.jpg?raw=true "Data Preview")

![Image-3](https://github.com/ibrahim1023/dog-breed-classification/blob/main/preview_images/image-3.jpg?raw=true "Data Preview")

![Image-4](https://github.com/ibrahim1023/dog-breed-classification/blob/main/preview_images/image-4.jpg?raw=true "Data Preview")

## Models

| Model | Accuracy (Highest achieved) |
| :---  |     :---:      |
| `MobileNetV2` | 99.5 %|

## Predictions 

![Prediction Image](https://github.com/ibrahim1023/dog-breed-classification/blob/main/preview_images/final.jpg?raw=true "Prediction")

## Dependencies
* Pandas
* Numpy
* TensorFlow
* TensorFlowHub
* Sklearn
