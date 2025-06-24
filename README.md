# Sound Dataset Clustering

This repository contains a Jupyter Notebook that applies unsupervised clustering techniques to a dataset of unlabeled sound recordings. The goal is to extract meaningful patterns from audio using feature extraction, dimensionality reduction, and clustering evaluation.

## 🧠 Project Objective

- Extract Mel Spectrogram features from raw audio files.
- Explore the importance of dimensionality reduction in high-dimensional data.
- Apply and compare PCA and t-SNE for visualizing feature space.
- Cluster the data using K-Means and DBSCAN.
- Evaluate and interpret cluster quality using Silhouette Score and Davies-Bouldin Index.
- Visualize final clusters using t-SNE with KMeans labels.



> ⚠️ Note: Audio dataset is stored in Google Drive and must be manually downloaded for use.

- 🔗 Link to Dataset [Google Drive Folder](https://drive.google.com/file/d/1bme1IuScdIWjzFkYPOcWzFOgD50MS_zR/view)

.
# Load the Data

 unlabelled_data_path = ('/content/drive/My Drive/unlabelled_sounds')

## 🛠️ Technologies Used

- Python 3.10+
- Jupyter Notebook
- Librosa (audio feature extraction)
- Scikit-learn (clustering, PCA, metrics)
- Seaborn / Matplotlib (visualization)

## 📊 Clustering Summary

- **K-Means** with `k=5` performed best, achieving:
  - Silhouette Score: ~0.27
  - Davies-Bouldin Index: ~1.26
- **DBSCAN** failed to form meaningful clusters with the provided parameters.
- **t-SNE** produced superior visual separability compared to PCA.

## 🧾 Assignment Coverage

✅ Feature extraction  
✅ Dimensionality reduction justification  
✅ PCA vs t-SNE visual comparison  
✅ KMeans vs DBSCAN with metric-based analysis  
✅ Final clustering visualization and conclusion

## ✍️ Author

**Valentine Tobechi Kalu**  
Course: Machine Learning Techniques II
Facilitator: Marvin Ogore

## 📎 License

This project is for academic and educational use only.
