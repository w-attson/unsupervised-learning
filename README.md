# Cryptocurrency Clustering with Unsupervised Learning

This project notebook (crypto_investments.ipynb) contains the following components:

* Data Import
  * Importing required libraries
  * Determine original data statistics
* Data Preparation
  * Use sklearn to transform data
  * Create DateFrame amd set index
* Original Data
  * Finding the best k value
    * Using k, fit data model from transformed data
    * Use Elbow Curve to determine which k value is the most suitable. 
  * Clustering with KMeans
    * Using determined k value, use predictive model on transformed data
    * Add predicted clusters to DataFrame
    * Create scatter plot to conduct visual analysis
* Principal Component Analysis (PCA)
  * Cluster Optimisation
    * Using PCA, use transformed data to determnine optimal clusters
    * Calculate the variance ratio
  * Finding the best k value
    * Using k, fit data model from transformed data
    * Use Elbow Curve to determine which k value is the most suitable. 
  * Clustering with KMeans
    * Using determined k value, use predictive model on transformed data
    * Add predicted clusters to DataFrame
    * Create scatter plot to conduct visual analysis
* Comparison and Visualisation
  * Determine the difference between each of the analysis conducted.
 
