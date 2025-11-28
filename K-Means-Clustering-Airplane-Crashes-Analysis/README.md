K-Means Clustering on Airplane Crashes Data



This project applies the K-Means Clustering algorithm to the Airplane Crashes dataset to identify hidden patterns using unsupervised machine learning. Since there is no target variable in this dataset, the objective is to automatically group similar records based only on numerical feature values.



The features used for clustering are Aboard (number of passengers on board), Fatalities (number of deaths), and Ground (number of people killed on the ground). These features help the model categorize airplane accidents based on severity and overall impact.



To build the model, ten different cluster values (k = 1 to 10) were initially tested. The Elbow Method was then used to determine the optimal number of clusters. The optimal value of k was found to be 2, indicating that the dataset naturally groups into two meaningful clusters. The k-means++ initialization method was applied to avoid the random initialization problem and to achieve better starting centroid placement for improved clustering performance.



The final result produced two clear clusters that group airplane accidents based on intensity, separating high-impact crashes from low-impact crashes. This project demonstrates a practical example of unsupervised learning, including the process of selecting features, scaling data, determining optimal cluster numbers, fitting the model, and interpreting results.

