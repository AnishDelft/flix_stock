# flix_stock

## Structure of the repo

 - The ```flixstock_train.ipynb``` file contains all the EDA, data preprocessing and Neural Network training code and explanations of choices being made
 - The ```flixstock_test.ipynb``` files contains the script to load the trained model and make predictions and generate the ```prediction.csv```
 - The ```ìmages_copy``` folder contains the images provided by the FlixStock team for this exercise
 - The ```attributes.csv``` contains the filename and it's associated labels
 - The ```model``` directory contains the serialized model stored which is used to make predictions. The ```weights``` for the model are 5.45 GB in size and can be shared as a drive link.

## Problem Statement

The problem is a multi-class, multi-label classification problem

## Solution Formulation

The solution is formulated as a transfer learning problem solved using a Resnet-50 model serving as the backbone network. On top of it, a three-pronged network has been developed which predicts the 3 labels using a single model.


