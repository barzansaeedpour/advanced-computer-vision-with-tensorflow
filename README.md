# Advanced Computer Vision with TensorFlow


This repository contains the advanced topics of Computer Vision from Coursera.org course on Advanced Computer Vision with TensorFlow


## Content:

- **Transfer Learning for binary classification** [(this file)](./01_transfer_learning_cats_dogs.ipynb)
    
    Binary Classification on cats and dogs dataset
- **Transfer Learning for multi-class classification** [this file](./02_Transfer_Learning_CIFAR_10.ipynb)
    
    Multi-Class classification on CIFAR-10 dataset

- **Object Localization** [this file](./03_Object_Localization.ipynb)

    In this lab, you'll build a CNN from scratch to:

    - classify the main subject in an image
    localize it by drawing bounding boxes around it.
    You'll use the MNIST dataset to synthesize a custom dataset for the task:

    - Place each "digit" image on a black canvas of width 75 x 75 at random locations.
    Calculate the corresponding bounding boxes for those "digits".
    The bounding box prediction can be modelled as a "regression" task, which means that the model will predict a numeric value (as opposed to a category)

    - Calculate the IOU (Intersection Over Union) metric to evaluate the model's performance
