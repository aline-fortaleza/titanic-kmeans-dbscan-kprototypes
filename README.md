# Project Summary – Unsupervised Clustering on the Titanic Dataset

This project applies unsupervised learning techniques to identify meaningful passenger groups in the Titanic dataset after removing the Survived label to ensure a purely exploratory analysis. The workflow includes preprocessing steps (handling missing values, encoding categorical variables, and scaling), followed by the application of K-Means, K-Prototypes, and DBSCAN to uncover patterns among passengers.

For K-Means, multiple metrics such as Elbow, Silhouette, Calinski-Harabasz, Davies-Bouldin, and BIC were evaluated, with the majority vote suggesting k = 5 as the optimal number of clusters (see simultaneous metric plots on pages 4–6). Clusters were then interpreted using decision-tree rule extraction (page 8), enabling a clear description of each group.

K-Prototypes was used to handle mixed numerical and categorical data without one-hot encoding, while DBSCAN identified density-based clusters and outliers (page 11). t-SNE visualizations were employed throughout to support interpretation.

Overall, the project demonstrates a complete unsupervised pipeline—from EDA and preprocessing to clustering evaluation and interpretation—revealing distinct behavioral and demographic passenger profiles.
