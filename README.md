This repository contains the implementation and analysis of an unsupervised learning framework for clustering music tracks using Beta-Variational Autoencoders (Beta-VAE). The project focuses on learning meaningful latent representations from music-related textual data and performing clustering without any labeled information.

Project Overview

The objective of this project is to explore unsupervised representation learning for music data. Song lyrics are transformed into numerical feature vectors, which are then passed through a Variational Autoencoder to obtain compact latent embeddings. These embeddings are used to perform clustering and analyze hidden structures within the dataset.

The project follows a step-by-step experimental pipeline starting from data preprocessing and ending with visualization and evaluation of clustering performance.

Methods Used

The project uses TF-IDF vectorization to convert song lyrics into high-dimensional feature vectors. A Beta-Variational Autoencoder is implemented to learn disentangled latent representations. Multiple clustering algorithms including K-Means, Agglomerative Clustering, and DBSCAN are applied on the learned latent space. Dimensionality reduction techniques such as PCA, t-SNE, and UMAP are used for visualization. Clustering quality is evaluated using Silhouette Score and Davies-Bouldin Index.

Technologies Used

The implementation is done using Python. PyTorch is used to build and train the Beta-VAE model. Scikit-learn is used for preprocessing, clustering, and evaluation. Matplotlib and Seaborn are used for visualization. All experiments are designed to be runnable on Google Colab using CPU.

Repository Structure

The data directory contains raw and processed datasets.
The notebooks directory contains step-by-step Jupyter notebooks for data loading, preprocessing, model training, clustering, and visualization.
The models directory contains the implementation of the Beta-VAE architecture.
The results directory stores generated figures and evaluation metrics.
The thesis directory contains the LaTeX source for the final project report.

Course Information

Course Name: CSE 715 – Neural Networks
Project Type: Unsupervised Learning Project
Student GitHub: https://github.com/LEXEMEE/CSE715

Future Work

Future extensions of this project may include multimodal learning using both lyrics and audio features, transformer-based embeddings for text representation, contrastive learning approaches, and more advanced clustering evaluation strategies.
