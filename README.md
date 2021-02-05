# CIFAR10-Classifiers

The CIFAR10 dataset had been downloaded from https://www.cs.toronto.edu/~kriz/cifar.html. The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. The archive contains the files data_batch_1, data_batch_2, ..., data_batch_5, as well as test_batch. Each of these files is a Python "pickled" object produced with cPickle.

In this project we train several classifiers to classify 10 different classes in CIFAR10 dataset to obtain an accuracy above 0.90.

In Classification-KNN.ipynb we train and tune parameters using GridSearch for a classfier pipeline by firt applying a dimension reduction model and then KNN. 
In Classification-SVM.ipynb we train and tune paramenter using GridSearch for a classfier pipeline by firt applying a dimension reduction model and then SVC 
In CNN.ipynb we train a convolutional neural network on GPU using both Adam and RMSprop optimizers with 100 epochs.
In TransferLearning.ipynb we implement ransfer learning using Resnet50 model as our base model and improve accuracy to 0.92

