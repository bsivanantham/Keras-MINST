# Keras-MINST

## Overview

We're going to build a model that recognizes handwritten digit images (MNIST). Developed using [TensorFlow](https://www.tensorflow.org/)   and the super simple [Keras](https://keras.io/)   Library. Wrapped into a Webapp using  [Flask](http://flask.pocoo.org/)  Micro Framework.

## Dependencies
Now, we are ready to install necessary dependencies. The list of dependencies we will be needing for our project are as follows:

1. tensorflow (1.5.0)
2. Keras (2.1.4)
3. Flask (0.12.2)
4. h5py ( 2.7.1)

You can install these all at the same time using the command:

```ruby
pip3 install tensorflow keras Flask h5py
```

## Convolutional Neural Network
In machine learning, a Convolutional Neural Network (CNN, or ConvNet) is a class of deep, feed-forward artificial neural networks that has successfully been applied to analyzing visual imagery. Convolutional Neural Networks are a type of neural network that makes the explicit assumption that the inputs are images, which allows us to encode certain properties into the architecture. There are three main types of layers to build ConvNet architectures: Convolutional Layer, Pooling Layer, and Fully-Connected Layer. We will stack these layers to form a full ConvNet architecture.

![alt text](https://github.com/bsivanantham/Keras-MINST/blob/master/CNN_architecture.png)


## Credits
The credits for this code go to [Python MINST](http://www.python36.com/mnist-handwritten-digits-classification-using-keras/) and [Siraj](https://github.com/llSourcell/how_to_deploy_a_keras_model_to_production) . I've merely created a wrapper to get people started.
