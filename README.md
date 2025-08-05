In this project, I applied the K-Means Clustering algorithm to group customers into distinct segments based on their Annual Income and Spending Score.

Steps followed:

Loaded and explored the customer dataset using Pandas.

Selected two important features: Annual Income and Spending Score.

Used the Elbow Method to find the optimal number of clusters by calculating WCSS (Within-Cluster Sum of Squares).

Trained the K-Means model with 5 clusters.

Assigned cluster labels to each data point using .fit_predict().

Finally, visualized the customer segments using Matplotlib and Seaborn, with clear color-coded groups and centroids.
