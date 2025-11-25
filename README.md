# Machine_Learning_Clustering_Models
A collection of self-practice machine learning clustering models, including K-Means Clustering and Hierarchical (Agglomerative) Clustering, implemented in Python using Scikit-learn.
Both models were applied to the Airplane Crashes dataset using three numerical features: Aboard, Fatalities, and Ground. After feature scaling and determining the optimal number of clusters, both K-Means and Hierarchical Clustering consistently identified 2 clusters as the optimal grouping.

To evaluate performance, the Silhouette Score was calculated for both clustering models, and both produced the same score of approximately 0.99919 (99.91%), indicating extremely well-separated and clearly defined clusters in the dataset. Since both algorithms reached the same optimal clusters and evaluation score, either model performs equally well for this particular dataset.
