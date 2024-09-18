## K-Means Clustering

K-Means Clustering is a popular **unsupervised learning algorithm** used to group data into **k clusters** based on feature similarities. It partitions the dataset into k groups by minimizing the distance between data points and their corresponding cluster centroids.

### Steps of the K-Means Algorithm:
1. **Initialization**: Randomly select k initial centroids from the data points.
2. **Assignment**: Assign each data point to the nearest centroid, forming k clusters.
3. **Update**: Recalculate the centroids by taking the mean of all data points assigned to each cluster.
4. **Repeat**: Reassign data points and update centroids until the centroids no longer move significantly or the maximum number of iterations is reached.

### Key Features:
- The algorithm is iterative and seeks to minimize **intra-cluster variance**.
- Requires pre-specification of the number of clusters (**k**).
- Sensitive to initial centroid placement, often requiring multiple runs to get optimal results.

### Applications:
- Customer segmentation
- Image compression
- Document clustering
- Market basket analysis

### Advantages:
- Simple and easy to implement.
- Scales well to large datasets.
- Efficient for low-dimensional data.

### Limitations:
- Requires the number of clusters (**k**) to be defined in advance.
- Sensitive to outliers and noise.
- Assumes spherical clusters of similar sizes.

### Common Variants:
- **K-Means++**: Improves centroid initialization to avoid poor clustering results.
- **Mini-Batch K-Means**: Optimizes K-Means for large datasets by using mini-batches to compute the centroids.
