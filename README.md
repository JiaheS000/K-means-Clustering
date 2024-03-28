# K-means-Clustering

This repository engaged in a task typically associated with machine learning, specifically within the domain of unsupervised learning. The focus is on implementing the K-Means algorithm, which is a cornerstone method for clustering analysis. The objective for this Jupyter notebook work was to develop functions that can find the closest centroids to given data points and subsequently recompute the centroid positions based on the mean of the data points assigned to each centroid.

The main accomplishments in this Jupyter Notebook are:

1: Find Closest Centroids: You implemented the find_closest_centroids function that takes a data matrix X and an array of centroid positions centroids. The function computes the distance between each data point and each centroid, assigning the closest centroid to each data point. This process is essential for the K-Means algorithm, as it forms the basis for clustering the data into distinct groups.

2: Compute New Centroids: Subsequently, you coded the compute_centroids function. This function recalculates each centroid's position by averaging the data points that have been assigned to it. This step is crucial in the iterative process of K-Means, refining the centroids' positions to better represent the clusters' centers.

3: Testing and Validation: Throughout the notebook, you were methodical in testing these functions using dummy or example data. These tests validate the correctness of your implementations, ensuring that the functions perform as expected.

In this Jupyter Notebook work, several outputs are generated:

1: The notebook produces several outputs essential for the K-Means clustering process. Initially, for each data point, an index of the nearest centroid is outputted. This is a direct result of the find_closest_centroids function and is fundamental for understanding the data structure and preliminary clustering.

2: Following this, the compute_centroids function provides new centroid positions. These outputs reflect the updated cluster centers after considering the assignment of data points to their nearest centroids. The iterative application of these two steps (alternating between assigning points to the nearest centroid and updating centroids' positions) would eventually lead to the convergence of the algorithm, which is the goal of K-Means.

3: A few visual outputs are also included in the notebook (which is a common practice for such algorithms), and plots that visualize the initial and updated positions of centroids and the clusters' formation are available in the Jupyter Notebook file.
