Recommended - open this repository in colab
https://colab.research.google.com/github/LorSong/ML_from_scratch/blob/master/

For better understanding of different algorithms I love implementing them on my own, trying not to peek at the code of other implementations.
I first try to study theory behind it - then put it in code.

# ML_from_scratch
Implementation of ML/DL algorithms using python (mostly NumPy). Also I will include here some custom layers/transformers and etc.

First - SoftmaxRegressor 
Implementation of Mini-batch Gradient Descent for Softmax Regression.

- Reached reasonable accuracy compared to Sklearn LogisticRegression
- Design compatible with Scikit-Learn pipelines
- Tested on text classification task. 
- For this task I made additional custom transformer, to make word-vectors of given text.

Second - Convolutional2D layer 
Implementration of spatial convolutional 2D layer.

At first, I made use of numpy and simple "for loops". Using NumPy, I couldn't make it compatible with tf.keras models. That's why I rewrited it using tensorflow functions. Comparing to tf.keras.Conv2D, mine was a bit slower during learning.

- Design compatible with tf.keras models
- Results on image classification tasks were same as tf.keras.Conv2D (using simple CNN architecture)
- Tested on image classification task (cifar10).


