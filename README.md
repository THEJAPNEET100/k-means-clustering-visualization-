# k-means-clustering-visualization-
This simple code in python is used to segregate unlabeled data into two groups. 

  First, the two center-points are selected randomly from the datset, these two center-points might be same. Then all the points are assigned label '0', this step is not necessary.

  After this, all points are checked whether they are nearer to first center or the other. The nearest center is assigned to the data-point and both the centers are shifted accordingly. The center here means the centroid of the points, which is just mean value of the features.

  This process is repeated until there is no change in position of the centroids. Pyplot is used to visualize how centroids are travelling through this process, first they are chosen randomly and then to their optimized location
