# K-means Clustering and PCA
## Principal component analysis
Principal component analysis (PCA) dimensionality-reduction method that is often used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information in the large set. 
### Procedure for PCA
steps for the PCA are as follows:
1. Center and scale the data
2. Compute the covariance or correlation matrix
3. Find the eigenvalues and the orthonormal eigenvectors of S.
4. Find the principal components.
5. Reduce the dimension of the data.
Here we use the PCA built in function from the package to complete our task
## K-means Clustering 
K-means clustering is a common example of an exclusive clustering method where data points are assigned into K groups, where K represents the number of clusters based on the distance from each group’s centroid. The data points closest to a given centroid will be clustered under the same category. A larger K value will be indicative of smaller groupings with more granularity whereas a smaller K value will have larger groupings and less granularity. K-means clustering is commonly used in market segmentation, document clustering, image segmentation, and image compression.
### Procedure of K-means Clustering
For a given dataset, k is specified to be the number of distinct groups the points belong to. \
Step 1: randomly pick k points as the center.\
Step 2: calculate the distance from each data point to the center\
Step 3: Now assign each data point to the closest center according to the distance.\
Step 4：Update the center point by taking the average of the points in each cluster group.\
Step 5: Repeat the Steps 2 to 4 until the center point does not change anymore
