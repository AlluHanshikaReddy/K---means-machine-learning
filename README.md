# K---means-machine-learning
# K-Means Clustering Tutorial

This repository contains the code, figures, and tutorial created for a machine-learning assignment. It focuses on understanding how to choose the optimal number of clusters in k-means using the Elbow Method and Silhouette Analysis.

---

## Contents of This Repository

- `tutorial.pdf` — Full written tutorial (<2000 words)  
- `kmeans_k_choice_tutorial.ipynb` — Jupyter Notebook with complete code  
- `figures/` — Saved images (elbow curve, silhouette plots, cluster plots)  
- `README.md` — This file  
- `LICENSE` — Usage licence (MIT by default)

---

##  What This Project Demonstrates

### 1. Elbow Method
- Calculates inertia (WCSS) for k = 1 to 10  
- Visualises the elbow curve  
- Helps detect the point of diminishing returns  

### 2. Silhouette Analysis
- Computes silhouette scores for k = 2 to 10  
- Includes a detailed silhouette plot for k = 4  
- Evaluates cluster separation and cohesion  

### 3. Visualising Clusters
- Plots clusters with different colours and markers  
- Highlights centroids  
- Saves images for use in the tutorial  

---

##  How to Run

Install required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn
