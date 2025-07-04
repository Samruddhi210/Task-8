# Task-8
 Title: Clustering with K-Means.
This project applies unsupervised learning using the K-Means Clustering algorithm on a multivariate dataset. The goal is to discover hidden patterns in unlabeled data by grouping similar observations into distinct clusters. The analysis begins by uploading and loading the dataset using pandas, followed by basic exploratory data analysis and preprocessing. To ensure better clustering performance and visualization, the data is normalized using StandardScaler, and then reduced to 2 and 3 dimensions using Principal Component Analysis (PCA) for visual clarity.
After preprocessing, the Elbow Method is used to determine the optimal number of clusters (k). Both the visual inertia curve and an automated method using the kneed library are implemented to find the “elbow” point. This is validated further using the Silhouette Score, a metric that evaluates the quality of clustering by measuring intra-cluster similarity and inter-cluster dissimilarity. The K-Means algorithm is then fit to the data with the optimal value of k, and the resulting cluster labels are assigned to each data point.
For cluster visualization, a color-coded 2D scatter plot using PCA-reduced components is created to show the separation of clusters. To make the plots more informative, cluster centroids are overlaid on the visualizations, and seaborn is used for enhanced aesthetics. An optional 3D scatter plot using three PCA components is included for deeper insight into high-dimensional relationships.

The project goes beyond the basics by incorporating innovative techniques, such as:-
1) Cluster Profiling: computing feature-wise averages per cluster to understand what characterizes each group.
2) Radar Plots: to visually compare cluster profiles across features.
3) Silhouette Analysis Plot: to show the distribution of silhouette scores within each cluster.
4) Comparison with other clustering algorithms like Agglomerative Clustering, along with Silhouette-based performance evaluation.
5) Interactive visualizations using Plotly, enhancing interactivity for dashboards or presentations.
6) Exporting clustered results to CSV, making the analysis reusable for downstream tasks.
Overall, this project demonstrates a full pipeline of unsupervised learning — from data loading, dimensionality reduction, and model fitting, to rigorous cluster evaluation and visual storytelling — and stands as a strong portfolio piece for machine learning and data science applications.

