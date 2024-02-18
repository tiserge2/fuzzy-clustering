# Implementation of the Fuzzy C-Means Segmentation
This is a segmentation method based on the fuzzy clustering algorithm.

Fuzzy cmeans (FCM) is a method of clustering which allows one piece of data to belong to two or more clusters. This method (developed by Dunn in 1973 and improved by Bezdek in 1981) is frequently used in pattern recognition. It is based on minimization of the following objective function:

![alt text](https://github.com/tiserge2/fuzzy-clustering/blob/main/objective_function.png?raw=true)

where m is any real number greater than 1, uij is the degree of membership of xi in the cluster j, xi is the ith of d-dimensional measured data, cj is the ddimension center of the cluster, and ||*|| is any norm expressing the similarity between any measured data and the center.

Fuzzy partitioning is carried out through an iterative membership uij and the cluster centers cj

## Centers Vectors Compuation

![alt text](https://github.com/tiserge2/fuzzy-clustering/blob/main/centers_compute.png?raw=true)

## Membership Matrix update

![alt text](https://github.com/tiserge2/fuzzy-clustering/blob/main/membership_update.png?raw=true)

## Some Results 