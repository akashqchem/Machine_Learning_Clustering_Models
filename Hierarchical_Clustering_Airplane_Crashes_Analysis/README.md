Agglomerative Hierarchical Clustering - Airplane Crashes Data –



This project applies Agglomerative Hierarchical Clustering on the Airplane Crashes dataset to identify natural groups in the data using unsupervised machine learning. Since there is no target variable, the goal is to automatically group similar crash events based only on numerical feature values.



Features Used



The following three features were selected from the dataset for clustering:



1. Aboard (number of people onboard)



2\. Fatalities (number of deaths)



3\. Ground (number of people killed on the ground)



These features help group airplane crash events based on the severity and impact of the incident.





Modeling Approach



1. Feature scaling was applied to ensure fair distance measurement among features.



2\. The dendrogram method was used to visually determine the optimal number of clusters.



3\. To improve visibility, a sample of 200 data points was used for the dendrogram.



4\. The optimal number of clusters was found to be 2, based on the largest vertical distance in the dendrogram.



5\. The Agglomerative Hierarchical Clustering model was trained using the Ward linkage method.





Outcome



The model successfully formed two meaningful clusters that separate airplane crash events based on severity level.

Cluster labels were assigned to each data point using the fit\_predict() function.



Summary



This project demonstrates the complete process of performing hierarchical clustering including:



1. Selecting numeric features



2\. Scaling the data



3\. Constructing and reading a dendrogram



4\. Determining optimal clusters



5\. Training the Agglomerative Hierarchical Clustering model



6\. Assigning cluster labels to the dataset

