---
layout: archive
title: "Project"
permalink: /project/
author_profile: true
---

### Spotify Music Classification
**[Report](https://erichu12138.github.io/files/ml_capstone_spotify.pdf)** | **[Code](https://github.com/erichu12138/erichu12138.github.io/blob/master/files/ml_capstone_code.ipynb)** 

In this project, I built machine learning models based upon 45,000 songs from Spotify API. After careful preprocessing, train/test split, and normalization, I adopted dimensionality reduction and clustering methods including PCA, T-SNE, and MDS. Then, I used the silhouette score to determine the optimal number of clusters and added the result of k-means as an extra label to boost classification efficiency. Eventually, I classified 5,000 songs into 10 genres via 4 models (SVM/Neural Network/Random Forest/Adaboost) under the convention for supervised learning. Model performances were evaluated using the ROC curve and the highest AUC score achieved was 0.92/1.00.