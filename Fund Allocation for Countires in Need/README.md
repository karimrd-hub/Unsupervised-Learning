# Fund Allocation For Countries in Need Using Unsupervised Learning

## Project Overview
This project implements various clustering techniques to help an international association (an NGO) make data-driven decisions for allocating $10 million in aid to countries most in need. The analysis uses socio-economic and health factors to categorize countries based on their development needs.

## Data
The project uses Country-data.csv which contains various socio-economic and health indicators for different countries, including:
- GDPP
- Income indicators
- Child mortality rates
- Health metrics
- Other development factors

## Techniques Implemented
The analysis employs multiple unsupervised learning techniques:

1. **Principal Component Analysis (PCA)**
   - Dimensionality reduction
   - Feature importance analysis

2. **Clustering Algorithms**
   - K-means Clustering
   - DBSCAN (Density-Based Spatial Clustering)
   - Hierarchical Clustering

## Methodology
1. Data preprocessing and exploration
2. Feature Engineering : combining the attributes into 3 main categories [health, finance, trade] scaling and normalization
3. PCA implementation for dimensionality reduction
4. I created 2 datasets : the first contains 3 attributes : [health, finance, trade] while the 2nd contains the columns left after applying PCA (in our case 3 colmns are left)
5. Application of multiple clustering techniques on the 2 datasets : k-means, dbscan, hierarchical clustering
6. Cluster analysis and interpretation
7. Country categorization based on aid priority

## Tools Used
- Python
- pandas
- scikit-learn
- matplotlib
- seaborn



## Implementation
The complete implementation can be found in the Jupyter notebook: clustering-pca-k-means-dbscan-hierarchical.ipynb

## Project Goal
The primary objective is to identify and categorize countries based on their socio-economic conditions to ensure effective allocation of the $10 million aid fund to the most deserving countries.

## Expected Outcome
- Clearly categorized groups of countries based on development needs
- Data-driven insights for aid allocation
- Strategic fund distribution recommendations
- Identification of countries requiring immediate assistance
