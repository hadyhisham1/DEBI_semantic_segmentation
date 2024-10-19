# DEBI Semantic Segmentation Project

## Description
This repository contains the code and resources for a semantic segmentation project. The project aims to classify objects in an image by assigning a unique color to different objects up to 29 classes.

## Files and Directories
- **Models**: This directory stores the training notebooks for all models.
- **Reports**: This directory contains the report for the U-Net model.
- **preprocessing.ipynb**: Jupyter Notebook containing the preprocessing steps for the dataset.

## Dataset 
The dataset used in this project consists of 3-channel images as input, with a shape of (width, height, 3). The output is also 3-channel images, shaped (width, height, ID), where "ID" corresponds to the color ID specified in the labels CSV file. You can download the processed dataset from the following link: [Processed Dataset](https://www.kaggle.com/datasets/hadyhishammahmoud/segmentation-dataset/data).

## Video Demonstration
<iframe width="640" height="360" src="https://www.youtube.com/embed/7TJNe-7yN68" frameborder="0" allowfullscreen></iframe>
