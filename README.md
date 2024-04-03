# ML-assignment-4
K-means Algorithm in Machine Learning

This is a machine learning exercise that implements the K-means algorithm for image compression. The K-means algorithm is a method for automatically clustering similar data points.

The first step of the K-means algorithm is to randomly initialize K cluster centroids, and then proceed an iterative procedure that repeatedly assigns examples to their closest centroids, and then calculates the centroids based on the assginments. The K-means algorithm will always converge to a final set of means for the centroids.

In this case, we use the find_closest_centroid function to find the closet centroids and the compute_centroids function to compute the centroids. Then, we run the K-means algorithm on a toy 2D dataset to understand how K-means works. We set 3 centroids and 10 iteration times to observe how different clusters are created based on the initial points chosen.

Finally, we use the K-means algorithm to select the 16 colors that will be used to represent the compressed image. Specifically, we treat each pixel in the original image as a data sample and use the K-means algorithm to find the 16 colors that best group (cluster) the pixels in the three-dimensional RGB space. Once we have computed the cluster centroids on the image, we use the 16 colors to replace the pixels in the original image.
