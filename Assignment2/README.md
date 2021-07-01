# README
## Assignment 2
This assignment is part of CS6910 course of IIT Madras - Fundamentals of Deep Learning.
Get the problem statement here -https://wandb.ai/miteshk/assignments/reports/Assignment-2--Vmlldzo0NjA1MTU

We have completed 2 parts - namely part A and part B of this assignment.
### Part A: 

**convolutional neural network**  or **CNN**s a class of Deep neural network, most commonly applied to analyze visual imagery.
We implement a 5-layered CNN and dense layers at the end of the model. Dropout has also  been implemented to combat any overfitting in the network. This has been done with the help of interactive colab notebooks (who, oh so graciously provide us with, athough scarce but ,free gpus to experiment with). 

We use wandb tool to make multiple runs as hyperparameter tuning experiments , visualize the results and rationalize the inferences from them.


### Part B 
**Transfer learning** is a research problem in machine learning that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem. 

In this task we take a model previously trained on the imageNet dataset and apply it on our iNaturalist dataset.  This is done in two sections: Pre-training and Fine-tuning.
In pretraining we keep the convolutional feature learning layers of the base model, freeze it and add a few layers to make inference on our data.  After we learn these few layers, we unfreeze the base model and train on our data, albeit with a small learning rate, so  that the model adapts slowly to the training data while retaining the previous learning.


We have implemented this idea using 4 different  widely known base models, with many more possible configurations. It has been done in the form of colab notebooks with support a of interactive environment.


