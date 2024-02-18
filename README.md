# Implementation of the Fuzzy C-Means Segmentation
This is a segmentation method based on the fuzzy clustering algorithm.

Fuzzy cmeans (FCM) is a method of clustering which allows one piece of data to belong to two or more clusters. This method (developed by Dunn in 1973 and improved by Bezdek in 1981) is frequently used in pattern recognition. It is based on minimization of the following objective function:

<p align="center">
  <img src="https://github.com/tiserge2/fuzzy-clustering/blob/main/figures/objective_function.png?raw=true" width="600" />
</p>

where m is any real number greater than 1, uij is the degree of membership of xi in the cluster j, xi is the ith of d-dimensional measured data, cj is the ddimension center of the cluster, and ||*|| is any norm expressing the similarity between any measured data and the center.

Fuzzy partitioning is carried out through an iterative membership uij and the cluster centers cj

## Centers Vectors Compuation

<p align="center">
  <img src="https://github.com/tiserge2/fuzzy-clustering/blob/main/figures/centers_compute.png?raw=true" width="200" />
</p>

## Membership Matrix update

<p align="center">
  <img src="https://github.com/tiserge2/fuzzy-clustering/blob/main/figures/membership_update.png?raw=true" width="200" />
</p>


## Some Results 

### Segmentation result and residual from membership matrix at step 1

<p align="center">
  <img src="https://github.com/tiserge2/fuzzy-clustering/blob/main/figures/original.png?raw=true" width="200" />
  <img src="https://github.com/tiserge2/fuzzy-clustering/blob/main/figures/segmentation_step_1.png?raw=true" width="200" />
  <img src="https://github.com/tiserge2/fuzzy-clustering/blob/main/figures/residual_step_1.png?raw=true" width="200" />
</p>

### Segmentation result and residual from membership matrix at step 40

<p align="center">
  <img src="https://github.com/tiserge2/fuzzy-clustering/blob/main/figures/original.png?raw=true" width="400" />
  <img src="https://github.com/tiserge2/fuzzy-clustering/blob/main/figures/segmentation_step_40.png?raw=true" width="200" />
  <img src="https://github.com/tiserge2/fuzzy-clustering/blob/main/figures/residual_step_40.png?raw=true" width="400" />
</p>