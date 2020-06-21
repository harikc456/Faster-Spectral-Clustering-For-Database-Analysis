# Faster-Spectral-Clustering-For-Database-Analysis

Database Analysis using Spectral Clustering and Laplacian Centrality

Laplacian Centrality is used to measure the local centrality of a node. It helps in finding the degree of importance of a node in a graph

The given database is converted into a graph where nodes are tables and edges are the foreign key relationship between the tables.

In case of sharding a database it is important to know the degree of imporantance of tables to each other. So Laplacian centrality is useful measure to determine that.

A Spectral Custering with Ng-Jordan-Weiss Algorithm and Linear Time k-Means Clustering is implemented to cluster the database based on the centraility.

The ideas implemented on the above codes from the paper

* Laplacian centrality: A new centrality measure for weighted networks
  - https://www.sciencedirect.com/science/article/pii/S0020025511006761
  
* A Linear Time-Complexity k-Means Algorithm Using Cluster Shifting
   - https://ieeexplore.ieee.org/document/7065640
