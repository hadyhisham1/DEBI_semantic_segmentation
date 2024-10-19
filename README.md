# DEBI Semantic Segmentation Project

## Description
This repository contains the code and resources for a semantic segmentation project. The project aims to classify objects in an image by assigning a unique color to different objects up to 29 classes.

## Files and Directories
- Models: This directory stores the training notebooks for all models.
- Reports: This directory contains report for unet model.
- preprocessing.ipynb: Jupyter Notebook containing the preprocessing steps for the dataset.


## Dataset 

The dataset used in this project consists of 3-channel images as input, with a shape of (width, height, 3). The output is also 3-channel images, shaped (width, height, ID), where "ID" corresponds to the color ID specified in the labels CSV file. You can download the processed dataset from the following link: [Proccessed Dataset](https://www.kaggle.com/datasets/hadyhishammahmoud/segmentation-dataset/data). 
