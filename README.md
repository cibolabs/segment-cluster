# Clustering Landscape Segments
This is a super simple example of clustering a set of polygons with attributes into a defined number of classes using KMeans.

The notebook reads the spatial data (within a bounding box), allows selection of clustering parameters, and computes the silhouette score to help determine the optimal number of classes.

The resulting cluster number can be saved into a new spatial file.

To check out the data you'll need [DVC](https://dvc.org/) installed with Cibo Labs public S3 remote added:

`dvc remote add -d cibo-dvc s3://cibo-dvc/`

Or grab the data from OneDrive.

Example output:

![alt text](https://github.com/petescarth/segment-cluster/blob/main/example_clusters.png?raw=true)