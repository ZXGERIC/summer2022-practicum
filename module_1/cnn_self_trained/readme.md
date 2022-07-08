## Overview

This cnn_self_trained folder contains jupyter notebooks that process data and train / tune the model. 

## Structure

| Module  | Note |
| ------------- | ------------- |
| Preprocess_Data.ipynb   | Preprocess image data  |
| Hyperparameter_Tuning.ipynb   | Tune hpyer parameters  |
| CNN_Self_Trained_Model.ipynb    | Run the model end to end  |


## Prerequisite
- Google Drive
- Google Colab

## Run the Code

- Download code from this folder
- Download Asurion image data and place it under Google drive folder named 'practium'
- Run Preprocess_Data.ipynb
  - remove noisy image
  - reorganize data in a folder layout in preparation for deep learning
- Run Hyperparameter_Tuning.ipynb
  - find the best model based on various # of units and learning rate
- Run CNN_Self_Trained_Model.ipynb
  - run the model end to end
  - visualize and save the model
