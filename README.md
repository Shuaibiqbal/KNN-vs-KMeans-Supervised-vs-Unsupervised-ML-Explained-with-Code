# KNN-vs-KMeans-Supervised-vs-Unsupervised-ML-Explained-with-Code
A practical comparison between k-Nearest Neighbors (k-NN) and k-Means Clustering using Scikit-Learn. Includes code, explanations, visualizations, and evaluation metrics to demonstrate the difference between supervised and unsupervised learning.

This project provides a practical and visual comparison between two popular machine learning algorithms — **k-Nearest Neighbors (k-NN)** and **k-Means Clustering**. Both rely on distance metrics but serve different purposes in the ML world.

---

## 📌 Table of Contents

- [Introduction](#introduction)
- [Algorithms Covered](#algorithms-covered)
- [Dataset](#dataset)
- [Code Overview](#code-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Key Takeaways](#key-takeaways)
- [License](#license)

---

## 🧠 Introduction

- **k-NN** is a **supervised learning** algorithm used for classification and regression.
- **k-Means** is an **unsupervised learning** algorithm used for clustering.

This project demonstrates how both algorithms work using the same dataset (Digits dataset from `sklearn`) and compares their performance, methodology, and results.

---

## 📘 Algorithms Covered

| Algorithm   | Type              | Purpose            | Key Idea                                   |
|-------------|-------------------|--------------------|--------------------------------------------|
| k-NN        | Supervised        | Classification     | Predict label based on closest neighbors   |
| k-Means     | Unsupervised      | Clustering         | Group similar data into k clusters         |

---

## 📂 Dataset

We use the `digits` dataset from `sklearn.datasets`, which consists of:
- 1,797 handwritten digit images (8x8 pixels)
- 64 features per sample
- 10 classes (digits 0–9)

---

## 🧾 Code Overview

- 📁 `knn_vs_kmeans_comparison.py`: Main Python script that:
  - Loads and scales the data
  - Trains k-NN for classification
  - Trains k-Means for clustering
  - Evaluates both models
  - Visualizes predictions

---

## 💻 Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/knn-vs-kmeans.git
   cd knn-vs-kmeans
