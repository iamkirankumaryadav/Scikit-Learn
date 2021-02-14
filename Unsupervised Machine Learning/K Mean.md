# K Mean Clustering

An **Unsupervised** Machine Learning Technique

Identify **Cluster** | Group of Data Object in a Dataset

### What is Clustering?
- A Set of technique to **Partition** Data into Groups | Clusters | Segments
- Groups of Data Objects that are more **Similar** to other Objects in their Cluster then they are to Data Objects in other **Clusters**

### Categories of Clustering

#### 1. Partitional Clustering
- Divide Data Objects in **Non Overlapping Group**
- An Object can be a **Member** of only One Cluster
- **K** : Number of Clusters
- An **Iterative** Process
- Works  well when **Clusters** have **Spherical** Shape.

#### 2. Hierarchical Clustering

a. **Agglomerative** Clustering
- **Bottom Up** Approach
- **Merge** two Points that are most similar untill all points have been merged into a **Single** Cluster.

b. **Divisive** Clustering
- **Top Down** Approach
- Starts will all points as One Cluster and **Splits** the least similar clusters at each step until only **Single** Data Points remain.
- Sensitive to **Noise** and **Outliers**.

c. **Density** Based Clustering
- Cluster Assignment is based on the **Density** of Data Points in a region.
- Clusters are Assigned where there are **High Density** of Data Points seperated by **Low Density** regions.
