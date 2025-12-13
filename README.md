**Dynamic Social Media Trend Clustering**
A Python-based machine learning project that detects, clusters, and analyzes emerging social media trends.
It leverages text embeddings, TF-IDF, and clustering algorithms to group similar posts and identify trending topics dynamically.
## Table of Contents

- [Overview](#overview)  
- [Features](#features)      
- [Technologies Used](#technologies-used) 
- [Project Structure](#project-structure)  
- [Clustering Methods](#clustering-methods)  
- [Metrics & Evaluation](#metrics--evaluation)  
  
## Overview

This project collects social media posts and automatically detects emerging trends by clustering similar content. It supports multiple vectorization methods (TF-IDF and SBERT embeddings) and clustering algorithms (K-Means, BIRCH, Hierarchical Clustering).
## Features

- Collects and processes social media posts (text data)  
- Cleans and preprocesses text (stopwords removal, lowercasing, filtering)  
- Converts text into numerical representations (TF-IDF, SBERT embeddings)  
- Clusters posts using KMeans, BIRCH, or Hierarchical Clustering  
- Evaluates cluster quality with metrics (Silhouette Score, Davies-Bouldin Index, Calinski-Harabasz Index)  
- Visualizes clusters and trends  

---
1. Open the notebook `trend_clustering.ipynb` in Jupyter Notebook or JupyterLab.  
2. Make sure all required libraries are installed:  
   ```bash
   pip install -r requirements.txt
**##Technologies Used**

Python

Jupyter Notebook

scikit-learn (clustering & metrics)

sentence-transformers (SBERT embeddings)

pandas, numpy (data processing)

matplotlib, seaborn (visualization)
**Project Structure**
social-media-trend-clustering
├── support/
      |└── mlTaasks.ipynb               # Main Jupyter Notebook
      └──  BERTopic(HDBScan).ipynb
├── data/                               # Social media datasets (CSV files)
├── requirements.txt                    # Python dependencies
├── others/                             # video, report and slides
└── README.md                           # Project documentation
## Clustering Methods
- KMeans
- BIRCH
- Hierarchical Clustering
- Agglomerative
- HDBSCAN
- Gaussian Mixture
**Metrics & Evaluation**

Silhouette Score: Measures how well each post fits its cluster.

Davies-Bouldin Index: Measures cluster similarity; lower is better.

Calinski-Harabasz Index: Measures cluster separation; higher is better.
