# CNNClassifier
Image classification using Convolutional Neural Network (CNN)

# Multi-Class Image Classifier using a Convolutional Neural Network (CNN)

# The Dataset:
1)The CIFAR-10 is a labeled subset of 80 million tiny images dataset. It was collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton. (View on official website: https://www.cs.toronto.edu/~kriz/cifar.html)
2)The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 
3)The dataset is divided into five training batches and one test batch, each with 10000 images. 
4)The test batch contains exactly 1000 randomly-selected images from each class. 
5)The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class. 
6)The classes are completely mutually exclusive. 
 
# Extracting the data:
1)The CIFAR-10 dataset consists of 5 batches, named data_batch_1, data_batch_2, and so on, and each file packs the data using the pickle module in python.
2)In order to get the data we must unpickle the files and merge them together.

# Another way to extract the data is to import it using Keras

# Tags
Convolutional Neural Network (CNN), Image Classification, Supervised Learning, Keras, Optimization, Regularization, Numpy, Matplotlib

# Optimizer: Adam (Combines advantages of rmsprop and momentum)

# Regularization: Dropout

# Evaluation metric: Accuracy
