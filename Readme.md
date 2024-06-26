# **Classifying CIFAR images using CNN**

**Hugo Hiraoka - hhiraoka.w@gmail.com**

CIFAR-10 (Canadian Institute For Advanced Research) is a collection of images with 10 different classes representing airplanes, cars, birds, 
cats, deer, dogs, frogs, horses, ships, and trucks. CIFAR-10 is a set of images that can be used to teach a computer how to recognize objects.

![CIFAR-10 images](https://i.imgur.com/CV8YFvJ.png)

The CIFAR-10 dataset consists of 60000 32x32x3 i.e. color images in 10 classes, with 6000 images per class. There are 50000 training images and 
10000 test images ( https://www.cs.toronto.edu/~kriz/cifar.html)

The CIFAR-10 images are low-resolution (32x32x3) and allow researchers to different algorithms to see what works better. Various kinds of 
convolutional neural networks tend to be the best at recognizing the images in CIFAR-10.

We will build a multi-class classification algorithm to predict 10 different classes of the CIFAR-10 dataset using Convolutional Neural Networks
and try to improve our results, by trying to reduce overfitting by considering dropout, and increase the amount of neurons and convolutions.


