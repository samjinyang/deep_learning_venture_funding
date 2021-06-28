# Deep Learning Venture Funding

## Analysis Overview

The purpose of this analysis is to create various models to predict the success of venture funding firms.  To do this, we take a dataset filled with data on venture funding firms that have been successful, and those that have not been successful.  We will create various deep learning models that will run on the Sequential model basis.  The original model will run on 2 hidden layers with 8 and 4 nodes respectively.  Alternative Model 1 will only have 1 hidden layer, but with 20 nodes than the orignal model's first hidden layer.  Alternative Model 2 will also have one hidden layer but with 50 nodes.  Finally, Alternative Model 3 will have 2 hidden layers, with 50 and 25 nodes respectively.  The results are below:

## Results

Here are the following Loss and Accuracy scores for the following models:

* Original Model
  * Accuracy - 72.0%
  * Loss - .56
* Alternative Model 1
  * Accuracy - 72.6%
  * Loss - 0.67
* Alternative Model 2
  * Accuracy - 73.1%
  * Loss - 0.56
* Alternative Model 3
  * Accuracy - 73.0%
  * Loss - 0.56


## Summary

In summary, it seems like the accuracy or and the loss did not really change much across all the various deep learning models.  It definitely seems like adding more hidden layers and adding more nodes to the hidden layers did not improve the accuracy scores.  The Loss score was a little higher in Alternative Model 1, so having one hidden layer with less nodes is probably what contributed to that.  For future testing, maybe using a different activation layer for the hidden layers, or changing the features in the original training and testing dataset might result in more drastic changes.
