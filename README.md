# Neural-Network-Using-PyTorch
This repository contains a collection of PyTorch implementations for building and training neural networks. The code is designed to be simple and easy to understand, while still providing a solid foundation for more advanced applications.  

This repository contain implemenation regarding:

## AlexNet:

AlexNet is a deep convolutional neural network that was introduced in 2012 by Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton. It won the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) in 2012 by a large margin, and was one of the first deep learning models to demonstrate significant improvements in image classification accuracy. AlexNet consists of 5 convolutional layers, 3 max-pooling layers, and 3 fully connected layers. The network is trained using stochastic gradient descent with a cross-entropy loss function.

## GoogleNet:

GoogleNet, also known as Inception v1, is another deep convolutional neural network that was introduced by Google researchers in 2014. The network is characterized by its use of "inception" modules, which consist of multiple convolutional layers with different filter sizes and pooling operations. GoogleNet also uses global average pooling, which reduces the spatial dimensions of the feature maps to a single value per channel. The network is trained using stochastic gradient descent with a cross-entropy loss function.

## ResNet:

ResNet, short for residual network, is a deep convolutional neural network architecture that was introduced by Microsoft researchers in 2015. ResNet is known for its use of residual connections, which allow the network to learn residual mappings rather than attempting to learn the desired output directly. This approach allows for much deeper networks to be trained without suffering from vanishing gradients. ResNet consists of multiple residual blocks, each of which contains multiple convolutional layers and skip connections. The network is trained using stochastic gradient descent with a cross-entropy loss function.

Implementing these models on the CIFAR-10 dataset involves modifying the input and output dimensions of the networks to match the size of the CIFAR-10 images (32x32 pixels). The network architectures and training procedures are otherwise similar to their original implementations.
