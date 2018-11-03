# Data Scientist Nano Degree - Udacity 08/2018
# Project 2 : Developing-an-Image-Classifier-with-Deep-Learning

Description

This is the 2nd project for the Data Scientist Nanodegree. In this project, I used Pytorch and Deep learning techniques to classify iamges of flowers of 102 categories.

Prerequisites
Image Classifier Project work done on Windows 10 with anaconda package installed.

Installing
To install dependencies in anaconda envirnment, please use below command: conda create --name --file requirments.txt

Running the tests
1. How to use train.py
python train.py --gpu (use --gpu for GPU) --epochs --arch --checkpoint <checkpoint.pth>

Example: python train.py /home/rchukka/Desktop/aipnd-project/flowers/ --gpu --epochs 1 --arch vgg19_bn --checkpoint checkpoint_vgg19_e1.pth

2. predict.py
python predict.py --gpu --category_names cat_to_name.json

Example: python predict.py ./flowers/valid/1/image_06749.jpg ./image_classifier_model/checkpoint.pth --gpu --category_names cat_to_name.json

