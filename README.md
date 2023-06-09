# Advanced Computer Vision with TensorFlow


This repository serves as a roadmap to my advanced Computer Vision projects implemented with TensorFlow.

Please feel free to contribute in these repositories.


## Content:

- **Transfer Learning for binary classification** [(link)](https://github.com/barzansaeedpour/transfer-learning-for-binary-classification-tensorflow)

    This repository provides a practical guide on using transfer learning for binary classification tasks using TensorFlow.
     
- **Transfer Learning for multi-class classification** [(link)](https://github.com/barzansaeedpour/transfer-learning-for-multi-class-classification-CIFAR-10)
    
    This repository contains code and resources for performing multi-class classification on the CIFAR-10 dataset using transfer learning. 

- **Object Localization and Classification with One Network on MNIST Dataset** [(link)](https://github.com/barzansaeedpour/object-localization-and-classification-with-one-network)

    In this notebook, you'll build a CNN from scratch to:

    - classify the main subject in an image
    localize it by drawing bounding boxes around it.
    You'll use the MNIST dataset to synthesize a custom dataset for the task:

    - Place each "digit" image on a black canvas of width 75 x 75 at random locations.
    Calculate the corresponding bounding boxes for those "digits".
    The bounding box prediction can be modelled as a "regression" task, which means that the model will predict a numeric value (as opposed to a category)

    - Calculate the IOU (Intersection Over Union) metric to evaluate the model's performance

- **Predicting Bounding Boxes for Object Detection** [(link)](https://github.com/barzansaeedpour/predicting-bounding-boxes-for-image-detection)

    - In this repository we use tensorflow hub pretrained modules to detect objects in images and draw bounding boxes around the detected objects using the outputs.

- **Interactive Eager Few Shot Od Training Colab** [(link)](https://github.com/barzansaeedpour/interactive-eager-few-shot-od-training-colab)

    - In this repository we demonstrate fine tuning of a (TF2 friendly) RetinaNet architecture on very few examples of a novel class after initializing from a pre-trained COCO checkpoint.

- **Few-Shot Learning with Only 5 Images** [(link)](https://github.com/barzansaeedpour/few-shot-learning-using-just-5-images)


    - In this repository, we leverage the power of few-shot learning combined with a transfer learning approach to tackle the task of object detection.
