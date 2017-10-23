
# Unsupervised Machine Learning Project
## Creating Customer Segments



## Table of Contents  
- [Project Overview](#project-overview)
- [Install](#install)
- [Code](#code)


### <a name="project-overview"></a>Project Overview

This is the project on Unsupervised Machine Learning Techniques. The goal of this project is to best describe the variation in the different types of customers that a wholesale distributor interacts with. The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). This project involves with: 
- Selecting samples
- Feature relevance
- Feature scaling
- Outlier detection
- Principal component analysis (PCA)
- Dimensionality reduction
- Creating clusters
- Data recovery

### <a name="install"></a>Install

The project requires **Python 2.7** and the following Python libraries:

- [NumPy](http://www.numpy.org/)
- [Pandas](pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

[Jupyter Notebook](http://jupyter.org/) is necessary for running the .ipynb files to run the code for the project. 

### <a name="code"></a>Code

All of the code is provided in the Jupyter notebook `customer_segments.ipynb`. 

#### Result
- Based on the mean silhouette coefficient*, 2 clusters seems to give the best structure for the data. 
- Other than about 20 points (about 5% of data) and some points in the boundary between the two clusters, all of the HoReCa (Hotels/Restaurants/Cafes) data points are classified as cluster 0 and all of the retail data points are classified as cluster 1. 

* The silhouette coefficient for a data point measures how similar it is to its assigned cluster from -1 (dissimilar) to 1 (similar).