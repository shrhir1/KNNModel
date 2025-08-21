# KNNModel

📌 Project Overview
This project demonstrates the implementation of a K-Nearest Neighbors (KNN) classifier in Python for classification tasks.
The main objectives are:
Understand the fundamentals of KNN and its application to real-world datasets.
Build a KNN model from scratch (without relying solely on pre-built functions).
Compare performance on datasets such as MNIST handwritten digits and the Wine dataset.
Explore the impact of parameters like the number of neighbors (k) and distance metrics.

📂 Datasets
MNIST Handwritten Digits
A dataset of 70,000 grayscale images (28×28 pixels) of digits (0–9).
Used here for digit recognition tasks.
Wine Dataset
A dataset with chemical analysis of wines, with features such as alcohol, acidity, and phenols.
Used for classification into wine categories.

⚙️ Methods
Implemented data preprocessing (normalization, train/test split).
Built a KNN classifier from scratch:
Compute distances between data points.
Identify the nearest neighbors.
Perform majority voting for classification.
Evaluated models with accuracy scores.
Compared performance across different values of k and distance metrics.

📊 Results
KNN achieved competitive performance on MNIST digits when tuned properly.
Different k values influenced accuracy significantly.
Distance metrics (Euclidean vs. Manhattan) impacted results, with Manhattan sometimes being more robust to noise in higher dimensions.
