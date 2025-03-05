# Sound_Dataset_Clustering

This project explores clustering techniques on a dataset of unlabeled sound files using feature extraction, dimensionality reduction, and clustering algorithms.

## 📂 Project Structure
- `Clustering_assignment.ipynb`: Main Jupyter notebook with code, visualizations, and analysis.
- `unlabelled_sounds/`: Folder containing the `.wav` sound files.
- `README.md`: Project overview and instructions.

## 🚀 Methodology
1. **Feature Extraction:** Mel Spectrograms using `librosa`.
2. **Dimensionality Reduction:** PCA and t-SNE for better cluster visualization.
3. **Clustering Algorithms:** K-Means and DBSCAN.
4. **Evaluation Metrics:** Silhouette Score and Davies-Bouldin Index.

## 📊 Key Findings
- **Dimensionality Reduction:** Improved clustering performance by removing noise and redundancy.
- **Clustering Performance:** K-Means outperformed DBSCAN, achieving better-defined clusters.

## 🛠️ How to Run
1. Clone the repo: 
```bash
git clone https://github.com/yourusername/clustering-sound-data.git
