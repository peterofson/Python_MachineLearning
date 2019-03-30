## Clustering: k-means and GMM

Clustering algorithms are mostly straightforward: 
Points are assigned to centroids, and centroids are updated --- repeat until convergence.

Much of the difficulty in using clustering involves picking how many centroids to create and how to initialize those centroids. 
For the purposes of this assignment, focus will remain on the particulars of the algorithms.
You will be asked to code functions implementing k-means, soft k-means, and GMM clustering. This includes:

Assigning points (or parts of points) to clusters
Recalculating cluster / cluster centers.
Data: For this exercise, (derived) data in two dimensions will be used. 
In four differend instances, three clusters of data were derived from three different distributions. 
Sometimes the distributions overlap, other times they're more separated.
