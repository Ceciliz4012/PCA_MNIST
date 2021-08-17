# PCA_MNIST

## Introduction
This is a PCA implementation using SVD in a unsupervised manner.

The MNIST digit data set used for this project contains 3,600 images of handwritten digits (data provided in X_train.csv).
Each example is a 28 × 28 grayscale image, leading to 784 pixels. 
These images correspond to 3 different digits (’3’, ’6’, and ’9’). 

## About
In part (c), after running PCA on the data, created a 2D scatteer plot showing all the data points projected in the first 2 PC dimensions.
In addition, also created plots showing the same data points projected in the 100th and 101st PC dimensions.

In part (d), graphed the fractional reconstruction accuracy as a function of the number of principal components that are included. 
Calculated the number of principal components needed to achieve each of 90%, 80%, 70%, 60%, 50%, 40%, 30%, 20%, and 10% reconstruction accuracy.

In part (d), reconstructed the 1000th, 2000th, and 3000th examples using each of the different numbers of principal components. 

For example, the reconstruction for the 300th examples look like the following:

<img width="528" alt="Screen Shot 2021-08-17 at 10 36 28 AM" src="https://user-images.githubusercontent.com/71328646/129656644-bc5983fd-afa1-4d62-89e6-2a09249d0663.png">

