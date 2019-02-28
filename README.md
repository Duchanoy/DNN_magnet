# DNN_magnet
Dataset and Architectures for a hysteresis model of a magnetorheological damper complement of the article submitted to Sensors Journal   entitle  A Deep Neural Network based model for a kind of magnetorheological dampers.

## Data Sets
The datasets are formed by a pair of JSON files in the format *File_name.json* and *inp_File_name.json*. In the main file *File_name.json* can be found the actual measurements of the magnetorheological damper. 

The *inp_File_name.json* contain the damper design parameters used for the corresponding experiments.

__File description:__

| File_name     | Content    
| ------------- |:-------------:|
| One_fixed_damper.json     | These experiment is performed for a single damper configuration  |
| Test_experiments.json     | Test data set for dampers measures for a complete family of dampers      |  
| Testcases2.json | Test cases selected for the article   |   
| twofluidexp.json | This experiments are performed for a family of dampers configurations     |   

## Save neural networks 

This folder contains the files of the weights and bias resultant of the training for different architectures.

## Code files 
__Deep network.ipynb__  Contain the file for neural network training 
__Graficador pruebas.ipynb__  Contain the file for testing the network 

__Tensorboard logs.rar__ Contain the tensorboard logs for the training of each architecture 
