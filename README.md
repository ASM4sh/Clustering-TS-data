# Clustering Related Variables for Data Quality Assessment
As industrial systems become larger and the amount of data collected and stored surpasses the terabyte level, it increases difficulty to manually process data for system identification. Therefore, there is a need to develop and implement methods that can analyse a given data set and determine which regions can be used for system identification. This can be accomplished in three steps: preprocessing the data, assessing the data quality of the data set, and postprocessing the resulting assessment. One of the biggest challenges lies in preprocessing the data, due to the large number of different constraints and conditions that can be imposed on the given data set. Therefore, there is a need to examine the application of automated clustering methods to the preprocessing step.

This project seeks to implement different clustering methods to detect correlated variables and estimate the quality of the clustering results. Algorithms, such as k-means and hierarchical agglomerative clustering, successfully found groups of related variables. Both algorithms provided similar clusters. Of the considered methods, hierarchical agglomerative clustering was the fastest. Comparison of the result obtained with clustering to relationships that can be determined by correlation analysis shows that the results to be reasonable. The next research step would be to consider using prior knowledge about the correlated variables to investigate if clustering methods can identify more complicated dependencies.
