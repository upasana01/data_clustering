# data_clustering

# Amazon Food Reviews Clustering

This project aims to cluster Amazon food reviews using three different clustering algorithms: K-Means, K-Means++, and Agglomerative clustering. The goal is to visualize the clusters formed by each algorithm and compare their effectiveness.

## Goals

- Cluster data using K-Means, K-Means++, and Agglomerative clustering algorithms.
- Visualize the resulting clusters.
- Compare the clustering results of each algorithm.

## Data

The dataset used for this project contains Amazon food reviews, which include review text, ratings, and other relevant information. The data is located in the `data/` folder.

## Methodology

1. **Preprocessing**: Cleaned and prepared the data for analysis.
2. **Feature Extraction**: Used TF-IDF (Term Frequency-Inverse Document Frequency) to extract features from the review text.
3. **Dimensionality Reduction**: Implemented PCA (Principal Component Analysis) to reduce the dimensionality of the feature set.
4. **Clustering**: Performed clustering using:
   - K-Means
   - K-Means++
   - Agglomerative Clustering
5. **Visualization**: Generated plots to visualize the clusters formed by each algorithm.
6. **Comparison**: Analyzed and compared the results of the different clustering approaches.

## Implementation

The implementation can be found in the `code/` directory. The main steps are as follows:

- Data preprocessing scripts
- Feature extraction scripts using TF-IDF
- PCA implementation
- Clustering algorithms (K-Means, K-Means++, Agglomerative)
- Visualization of clusters

## Results

The results of the clustering algorithms, including various graphs and visualizations, are available in the `graphs/` directory. The presentation summarizing the findings can be found in the `presentation/` folder.

## Requirements

To run the code, you will need the following Python packages:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
