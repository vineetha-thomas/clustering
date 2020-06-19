# clustering

The following algorithms are implemented in the Jupyter Notebook. The performance is measured on MNIST dataset.

1. KMeans clustering
   - The initilaization of the centroids is done either by random selection or by picking the top K PCA components of input.
   - Performance of Kmeans clustering on the MNIST dataset is measured.

2. Hungarian algorithm
   - Hungarian algorithm matches the ground truth class labels(0 to 9) to the clustering labels, and hence we perform classification and can measure the classification accuracy.

3. Spectral Clustering
   - (https://en.wikipedia.org/wiki/Spectral_clustering)
   - Here too, Hungarian algorithm is used to match to ground truth labels and measure accuracy.
   
 4. kNN classifier
    - KMeans and Spectral Clustering is used along with kNN to achieve better classification accuracy on MNIST.
