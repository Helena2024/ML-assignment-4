# ML-assignment-4
K-means Algorithm in Machine Learning

This is a machine learning exercise of implementing the K-means algorithm for image compression. The K-means algorithm is a method to automatically cluster similar data points together. 

The first step of K-means algorithm is randomly initialize K cluster centroids, and then proceed an iterative procedure that repeatedly assigning examples to their closet centroids, and after that computing the centroids based on the assginments. The K-means algorithm will always converge to some final set of means for the centroids.

In this case, we use find_closest_centroid function to find the closet centroids and compute_centroids function to compute the centroids respectively. After that we run the K-means algorithm on a toy 2D dataset to help understand how K-means works. We set 3 centroids and 10 iteration times to observe how different clusters are created based on the initial points chosen.

Lastly, we use the K-means algorithm to select the 16 colors that will be used to represent the compressed image. Concretely, we treat every pixel in the original image as a data example and use the K-means algorithm to find the 16 colors that best group (cluster) the pixels in the 3- dimensional RGB space. Once we have computed the cluster centroids on the image, then use the 16 colors to replace the pixels in the original image.
