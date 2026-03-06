# Clustering-Analysis-using-Airlines-Dataset
This repository introduces clustering algorithms, including K-Means, Hierarchical Clustering, and DBSCAN, and provides hands-on experience in applying these techniques to a real-world dataset.

Clustering Methodology and Evaluation

A.1 Preprocessing
The dataset was preprocessed prior to clustering to ensure consistency and comparability across methods. Standardization and normalization techniques were applied where appropriate to prepare the data for distance-based algorithms.

A.2 Algorithms Applied
- K-Means Clustering
- Multiple values of K were tested using the Elbow Method to determine the optimal number of clusters.
- Evaluation was performed using the Silhouette Score to assess cluster cohesion and separation.
- Hierarchical Clustering
- Different linkage criteria (e.g., single, complete, average, Ward’s method) were explored to understand their impact on cluster formation.
- Dendrograms were used to visualize hierarchical relationships and determine suitable cut-off points for cluster selection.
- DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
- Parameters such as epsilon (\varepsilon ) and minimum points (minPts) were varied to evaluate sensitivity to density thresholds.
- The Silhouette Score was used to measure clustering quality, with particular attention to noise handling and cluster shape flexibility.

A.3 Evaluation Metrics
- Silhouette Score
- Applied to K-Means and DBSCAN to quantify intra-cluster similarity and inter-cluster separation.
- Scores closer to 1 indicated well-defined clusters, while values near 0 suggested overlapping clusters.
- Negative scores highlighted potential misclassification or poor parameter selection.
- Visual Inspection
- Cluster assignments were visualized to qualitatively assess separation, density, and distribution.
- Dendrograms (hierarchical), scatter plots (K-Means, DBSCAN), and parameter sensitivity plots were included to support quantitative findings.

A.4 Summary
The appendix documents the systematic exploration of clustering algorithms with varying parameter settings. By combining quantitative metrics (Silhouette Score) with qualitative visualization, the study ensured robust evaluation of clustering performance across different methods.


