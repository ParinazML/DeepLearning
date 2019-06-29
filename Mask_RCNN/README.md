# Introduction
This implementation is based on matterport Mask RCNN code which can be found here : https://github.com/matterport/Mask_RCNN 

The goal was implementation of a model for identifying stones in images.
The model has been trained on 54 images and validated on 9 images.

# Mask R-CNN for Object Detection and Segmentation

This is an implementation of [Mask R-CNN](https://arxiv.org/abs/1703.06870) on Python 3, Keras, and TensorFlow. The model generates bounding boxes and segmentation masks for each instance of an object in the image. It's based on Feature Pyramid Network (FPN) and a ResNet101 backbone.

The repository includes:
* Source code of Mask R-CNN built on FPN and ResNet101.
* Training code for MS COCO
* Pre-trained weights for MS COCO
* Jupyter notebooks to visualize the detection pipeline at every step
* ParallelModel class for multi-GPU training
* Evaluation on MS COCO metrics (AP)
* Example of training on your own dataset


# Getting Started
Demo file can be found here:
* [demo-stone.ipynb](samples/demo-stone.ipynb)
