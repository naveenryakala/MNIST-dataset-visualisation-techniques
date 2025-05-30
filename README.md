# MNIST Dataset Visualisation Techniques

This repository explores various dimensionality reduction and visualization techniques applied to the MNIST dataset, a classic dataset of handwritten digits. The goal is to understand how different methods can represent high-dimensional image data in lower dimensions for better interpretation and analysis.

## 📁 Folder Structure

MNIST-dataset-visualisation-techniques
│
├── ml-feature-insights.py # Exploratory analysis and feature insights of MNIST
├── highdim-to-2d.py # Reducing high-dimensional MNIST data to 2D
├── data-embeddings-visualized.py # Embedding digit data and visualizing patterns
├── pca.py # Principal Component Analysis on MNIST
├── tsne.py # T-SNE visualization of digit classes
├── umap.py # UMAP for fast and effective 2D embeddings
├── explorer.py # Combined visual explorer for PCA, T-SNE, UMAP
├── heatmaps-and-reductions.py # Heatmaps to understand pixel-level importance
├── requirements.txt # Required Python dependencies
└── README.md # Project overview and instructions

## 📌 Techniques Covered

1. **PCA (Principal Component Analysis)**  
   Linear technique to reduce data to 2D and visualize major variance directions.

2. **T-SNE (t-Distributed Stochastic Neighbor Embedding)**  
   Non-linear dimensionality reduction technique ideal for cluster visualization.

3. **UMAP (Uniform Manifold Approximation and Projection)**  
   Fast and scalable technique for high-quality 2D embeddings.

4. **Feature Insights**  
   Investigating individual pixel features, class distributions, and basic statistics.

5. **Heatmaps**  
   Pixel-level heatmaps for understanding digit structures.

## 🧪 Requirements

To install the dependencies,
run: pip install -r requirements.txt

📊 Dataset
We use the MNIST dataset available via sklearn.datasets.fetch_openml.

These scripts will load MNIST, apply the visualization technique, and display/save plots.

🙌 Credits
This project is inspired by learning resources and community contributors:

Scaler – Srikanth Varma

Krish Naik

Scaler, Udemy and open-source contributors

🏷 Hashtags
#MNIST #Visualization #PCA #TSNE #UMAP #DataScience #MachineLearning #DeepLearning #Python #OpenSource #AI #MLProjects #Embeddings#   M N I S T - d a t a s e t - v i s u a l i s a t i o n - t e c h n i q u e s  
 