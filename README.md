# DBSCAN Clustering on Wine Dataset

## Problem Statement
The objective of this project is to group wine samples into clusters based on their chemical properties using the DBSCAN clustering algorithm and identify noise points without predefined class labels.

## Algorithm Used
DBSCAN (Density-Based Spatial Clustering of Applications with Noise)

## Dataset
- Wine Dataset (scikit-learn)
- Samples: 178
- Features: 13 chemical attributes

## Steps Involved
1. Load the wine dataset
2. Perform feature scaling using StandardScaler
3. Apply DBSCAN clustering
4. Identify clusters and noise points
5. Visualize the clustering result

## Evaluation Metric
- Silhouette Score (if applicable)

## How to Run
```bash
pip install -r requirements.txt
python dbscan.py
Conclusion

DBSCAN successfully identified dense clusters in the wine dataset and detected noise points, demonstrating its effectiveness for density-based clustering.
