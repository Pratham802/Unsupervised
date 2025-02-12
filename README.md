# Unsupervised

### Problem Statement  

In Manhattan, residential houses contain various electrical appliances, each contributing to the overall energy consumption of the household. Understanding and analyzing these power usage patterns can help optimize electricity distribution and identify appliances that consume excessive or minimal amounts of energy.  

By grouping houses based on their total energy consumption, we can gain insights into power demand across different areas of the city. This categorization can assist in:  
- Efficient energy planning and distribution  
- Identifying high- and low-energy-consuming appliances  
- Encouraging energy-efficient practices  

This case study focuses on analyzing the power consumption of different household appliances and clustering houses based on their energy usage.

### Table of Content
1. Import Libraries.
   
2. Read Data.
   
3. Exploratory Data Analysis.
   
   3.1 Understand the Dataset

   3.2 Data Type

   3.3 Distribution of Variables

   3.4 Analysis of Outliers

   3.5 Summary Statistics

   3.6 Missing Values

   3.7 Prepare the Data

4. K-means Clustering.
   
   4.1 Identify the Optimal Number of Clusters
   
   4.2 Build the Model

   4.3 Analyze the Clusters

5. Hierarchical Clustering.

   5.1 Identify the Optimal Number of Clusters

   5.2 Build the Model

   5.3 Analyze the Clusters

6. DBSCAN.
    
   6.1 Build the Model

   6.2 Analyze the Clusters
    
7. Visualize the Clusters.

### Analysis and Conclusion.
The subplots above represent clusters formed by different algorithms. We can see that the K-means and hierarchical clustering have created 3 clusters, while the DBSCAN algorithm has grouped the data into 4 clusters.

The plots for K-means and hierarchical clustering show similarity in cluster formation. The DBSCAN algorithm has clustered houses based on the power consumption of the other appliances in the house. Also, the blue points in the DBSCAN plot represent the outliers identified by the algorithm.

We can see that some points overlap in the subplots, this is because we have projected a 7-D dataset to 2-D which is explaining only 65 percent of total variance in the original data.
