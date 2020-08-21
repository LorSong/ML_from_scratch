Recommended - open this repository in colab
https://colab.research.google.com/github/LorSong/ML_from_scratch/blob/master/

# ML_from_scratch
Implementation of some ML algorithms using python and numpy

First - SoftmaxRegressor:

Implementation of Mini-batch Gradient Descent for Softmax Regression.
Tested on text classification task. 
For this task I made additional custom transformer, to make word-vectors of given text.
(Design compatible with Scikit-Learn pipelines).

Second - Convolutional2D layer

Implementration of spatial convolutional 2D layer
Tested on image classification task (cifar10).
First I made use of numpy and simple "for loops", then rewrited using tensor flow functions
(Design compatible with tf.keras models)
