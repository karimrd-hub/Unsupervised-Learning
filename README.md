# A collection of projects demonstrating core unsupervised learning techniques, including clustering, dimensionality reduction, and recommendation systems

Development time: August 2024

These projects cover the full workflow, from exploratory data analysis (EDA) and data preprocessing to implementing and training unsupervised models and leveraging their outputs for insights and optimization.

## Projects Overview

### 1. Collaborative Recommendation

An item-based collaborative filtering system for movie recommendations using the MovieLens dataset.

**Techniques:** K-Nearest Neighbors, Cosine Similarity, Sparse Matrices

**Dataset:** 9,724 movies, 610 users (filtered to 2,121 movies, 378 active users)

**Key Features:**
- Sparse matrix representation for memory efficiency
- Returns top 10 similar movie recommendations with similarity scores
- Data filtering for quality recommendations

---

### 2. Fund Allocation for Countries in Need

Helps an international humanitarian NGO strategically allocate $10 million in aid by clustering 167 countries based on socio-economic and health indicators.

**Techniques:** K-Means, DBSCAN, Hierarchical Clustering, PCA

**Dataset:** 167 countries with indicators including child mortality, income, life expectancy, GDP, health spending, and trade metrics

**Key Features:**
- Comparison of three clustering algorithms
- PCA for dimensionality reduction
- Interactive world map visualization
- Country categorization: "Help Needed", "Might Need Help", "No Help Needed"

---

### 3. K-Means Implementation from Scratch

Educational project implementing the K-means clustering algorithm from scratch without using built-in ML library clustering functions. Applied to customer segmentation.

**Techniques:** Custom K-Means implementation, Elbow Method, Silhouette Analysis

**Dataset:** 200 mall customers with age, income, and spending score data

**Key Features:**
- Step-by-step algorithm implementation (initialization, distance calculation, assignment, convergence)
- Comparison with sklearn's KMeans
- Optimal cluster selection using elbow method

---

### 4. News Clustering

Groups news articles into clusters based on content similarity using NLP and unsupervised learning.

**Techniques:** TF-IDF Vectorization, K-Means, Hierarchical Clustering, PCA, NLTK

**Dataset:** 10,239 news articles (balanced subset of 204 articles used for training)

**Key Features:**
- Complete NLP pipeline: tokenization, stop word removal, Porter stemming
- TF-IDF feature extraction
- Cluster quality comparison via silhouette scores
- Hierarchical clustering achieved best results (Silhouette Score: 0.524)

---

## Technologies Used

| Category | Libraries |
|----------|-----------|
| Data Processing | pandas, numpy |
| Machine Learning | scikit-learn |
| NLP | NLTK |
| Visualization | matplotlib, seaborn, plotly |
| Sparse Data | scipy.sparse |

## Quick Comparison

| Project | Primary Algorithm | Dataset Size | Use Case |
|---------|-------------------|--------------|----------|
| Collaborative Recommendation | KNN + Cosine Similarity | 2,121 movies | Movie recommendations |
| Fund Allocation | K-Means, DBSCAN, Hierarchical | 167 countries | Aid distribution |
| K-Means Scratch | Custom K-Means | 200 customers | Educational |
| News Clustering | K-Means, Hierarchical + TF-IDF | 204 articles | Content organization |
