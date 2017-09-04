# Unsupervised Learning - Customer Segments

Data preparation:
* Feature rescaling - np.log
* Remove outliers - 1.5(Q3-Q1), Q1, np.percentile(25)

Plotting:
* Seaborn scatter matrix - [Paired Density and Scatterplot Matrix](http://seaborn.pydata.org/examples/pair_grid_with_kde.html)

Dimensionality Reduction:
* Principal component analysis
* Cumulative explained variance ratio

Clustering algorithm:
* Kmeans
* Gaussian Mixture 

The quality of clustering
* [Silhouette coefficient](http://scikit-learn.org/stable/modules/generated/sklearn.metrics.silhouette_score.html)

Data: 
* [Wholesale customers Data Set](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers) from UCI Machine Learning Repositor.
